# Compiler.CompileFromString Method 
 

Compiles a .NET assembly from the specified source code string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual CompilerResultsEx CompileFromString(
	AssemblyType netAssembly,
	string targetFile,
	string sourceCode,
	string mainClass,
	IEnumerable<string> referencedAssemblies = null,
	IEnumerable<string> resources = null,
	string iconFile = ""
)
```

**VB**<br />
``` VB
Public Overridable Function CompileFromString ( 
	netAssembly As AssemblyType,
	targetFile As String,
	sourceCode As String,
	mainClass As String,
	Optional referencedAssemblies As IEnumerable(Of String) = Nothing,
	Optional resources As IEnumerable(Of String) = Nothing,
	Optional iconFile As String = ""
) As CompilerResultsEx
```

**VB Usage**<br />
``` VB Usage
Dim instance As Compiler
Dim netAssembly As AssemblyType
Dim targetFile As String
Dim sourceCode As String
Dim mainClass As String
Dim referencedAssemblies As IEnumerable(Of String)
Dim resources As IEnumerable(Of String)
Dim iconFile As String
Dim returnValue As CompilerResultsEx

returnValue = instance.CompileFromString(netAssembly, 
	targetFile, sourceCode, mainClass, 
	referencedAssemblies, resources, 
	iconFile)
```

**C++**<br />
``` C++
public:
virtual CompilerResultsEx^ CompileFromString(
	AssemblyType netAssembly, 
	String^ targetFile, 
	String^ sourceCode, 
	String^ mainClass, 
	IEnumerable<String^>^ referencedAssemblies = nullptr, 
	IEnumerable<String^>^ resources = nullptr, 
	String^ iconFile = L""
)
```

**F#**<br />
``` F#
abstract CompileFromString : 
        netAssembly : AssemblyType * 
        targetFile : string * 
        sourceCode : string * 
        mainClass : string * 
        ?referencedAssemblies : IEnumerable<string> * 
        ?resources : IEnumerable<string> * 
        ?iconFile : string 
(* Defaults:
        let _referencedAssemblies = defaultArg referencedAssemblies null
        let _resources = defaultArg resources null
        let _iconFile = defaultArg iconFile ""
*)
-> CompilerResultsEx 
override CompileFromString : 
        netAssembly : AssemblyType * 
        targetFile : string * 
        sourceCode : string * 
        mainClass : string * 
        ?referencedAssemblies : IEnumerable<string> * 
        ?resources : IEnumerable<string> * 
        ?iconFile : string 
(* Defaults:
        let _referencedAssemblies = defaultArg referencedAssemblies null
        let _resources = defaultArg resources null
        let _iconFile = defaultArg iconFile ""
*)
-> CompilerResultsEx 
```


#### Parameters
&nbsp;<dl><dt>netAssembly</dt><dd>Type: <a href="T_DevCase_Interop_Managed_AssemblyType">DevCase.Interop.Managed.AssemblyType</a><br />The target kind of .NET assembly.</dd><dt>targetFile</dt><dd>Type: System.String<br />The target local file to create.</dd><dt>sourceCode</dt><dd>Type: System.String<br />The input source code to compile.</dd><dt>mainClass</dt><dd>Type: System.String<br />The name of the class that provides the entry point for the application.</dd><dt>referencedAssemblies (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The referenced assemblies.</dd><dt>resources (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The managed .NET resources.</dd><dt>iconFile (Optional)</dt><dd>Type: System.String<br />The icon used to set the appereance of the executable file.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Managed_CompilerResultsEx">CompilerResultsEx</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Managed.Compiler.CompileFromString(DevCase.Interop.Managed.AssemblyType,System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String},System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>The current CodeDomProvider does not support resource embedding.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Compiler">Compiler Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />