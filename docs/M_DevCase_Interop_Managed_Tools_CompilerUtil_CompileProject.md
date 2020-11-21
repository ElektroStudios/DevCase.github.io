# CompilerUtil.CompileProject Method (String, MsBuildVersion)
 

Compiles a Visual Studio project or solution.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CompileProject(
	string filepath,
	MsBuildVersion compilerVersion
)
```

**VB**<br />
``` VB
Public Shared Function CompileProject ( 
	filepath As String,
	compilerVersion As MsBuildVersion
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim compilerVersion As MsBuildVersion
Dim returnValue As String

returnValue = CompilerUtil.CompileProject(filepath, 
	compilerVersion)
```

**C++**<br />
``` C++
public:
static String^ CompileProject(
	String^ filepath, 
	MsBuildVersion compilerVersion
)
```

**F#**<br />
``` F#
static member CompileProject : 
        filepath : string * 
        compilerVersion : MsBuildVersion -> string 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The Visual Studio project or solution file.</dd><dt>compilerVersion</dt><dd>Type: <a href="T_DevCase_Interop_Managed_MsBuildVersion">DevCase.Interop.Managed.MsBuildVersion</a><br />The compiler version to build the source file.</dd></dl>

#### Return Value
Type: String<br />If the compiler operation succeeds, the return value is String, otherwise, the return value contains the error output generated by the compiler.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>compilerVersion</td></tr><tr><td>Exception</td><td>A 64-Bit compiler cannot run under a 32-Bit operating system.</td></tr><tr><td>Exception</td><td>Directory not found for the specified compiler version.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim compileResult As String = CompileProject("C:\Solution.sln", NetFxCompilerVersion.NetFx40x64)

If Not String.IsNullOrEmpty(compileResult) Then
    ' Show error output...
    MessageBox.Show(compileResult)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_CompilerUtil">CompilerUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_CompilerUtil_CompileProject">CompileProject Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />