# CompilerWorkDoneEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CompilerWorkDoneEventArgs(
	CodeDomProvider codeDomProvider,
	CompilerParameters compilerParameters,
	IEnumerable<CompilerWarning> compilerWarnings,
	IEnumerable<CompilerError> compileErrors,
	string sourceCode,
	string sourceFilePath,
	string targetFilePath,
	string tempDirectoryPath
)
```

**VB**<br />
``` VB
Public Sub New ( 
	codeDomProvider As CodeDomProvider,
	compilerParameters As CompilerParameters,
	compilerWarnings As IEnumerable(Of CompilerWarning),
	compileErrors As IEnumerable(Of CompilerError),
	sourceCode As String,
	sourceFilePath As String,
	targetFilePath As String,
	tempDirectoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim codeDomProvider As CodeDomProvider
Dim compilerParameters As CompilerParameters
Dim compilerWarnings As IEnumerable(Of CompilerWarning)
Dim compileErrors As IEnumerable(Of CompilerError)
Dim sourceCode As String
Dim sourceFilePath As String
Dim targetFilePath As String
Dim tempDirectoryPath As String

Dim instance As New CompilerWorkDoneEventArgs(codeDomProvider, 
	compilerParameters, compilerWarnings, 
	compileErrors, sourceCode, sourceFilePath, 
	targetFilePath, tempDirectoryPath)
```

**C++**<br />
``` C++
public:
CompilerWorkDoneEventArgs(
	CodeDomProvider^ codeDomProvider, 
	CompilerParameters^ compilerParameters, 
	IEnumerable<CompilerWarning^>^ compilerWarnings, 
	IEnumerable<CompilerError^>^ compileErrors, 
	String^ sourceCode, 
	String^ sourceFilePath, 
	String^ targetFilePath, 
	String^ tempDirectoryPath
)
```

**F#**<br />
``` F#
new : 
        codeDomProvider : CodeDomProvider * 
        compilerParameters : CompilerParameters * 
        compilerWarnings : IEnumerable<CompilerWarning> * 
        compileErrors : IEnumerable<CompilerError> * 
        sourceCode : string * 
        sourceFilePath : string * 
        targetFilePath : string * 
        tempDirectoryPath : string -> CompilerWorkDoneEventArgs
```


#### Parameters
&nbsp;<dl><dt>codeDomProvider</dt><dd>Type: System.CodeDom.Compiler.CodeDomProvider<br />The CodeDom provider.</dd><dt>compilerParameters</dt><dd>Type: System.CodeDom.Compiler.CompilerParameters<br />The compiler parameters used to build the target file.</dd><dt>compilerWarnings</dt><dd>Type: System.Collections.Generic.IEnumerable(<a href="T_DevCase_Interop_Managed_CompilerWarning">CompilerWarning</a>)<br />The compiler warnings.</dd><dt>compileErrors</dt><dd>Type: System.Collections.Generic.IEnumerable(CompilerError)<br />The compile errors.</dd><dt>sourceCode</dt><dd>Type: System.String<br />The source code string (if any).</dd><dt>sourceFilePath</dt><dd>Type: System.String<br />The source file path (if any).</dd><dt>targetFilePath</dt><dd>Type: System.String<br />The target .NET assembly filepath.</dd><dt>tempDirectoryPath</dt><dd>Type: System.String<br />The temporary files path used for the compiler.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs Class</a><br /><a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing Namespace</a><br />