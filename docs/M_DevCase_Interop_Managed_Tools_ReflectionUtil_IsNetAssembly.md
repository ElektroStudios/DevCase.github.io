# ReflectionUtil.IsNetAssembly Method 
 

Determines whether an exe/dll file is an .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsNetAssembly(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function IsNetAssembly ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = ReflectionUtil.IsNetAssembly(filepath)
```

**C++**<br />
``` C++
public:
static bool IsNetAssembly(
	String^ filepath
)
```

**F#**<br />
``` F#
static member IsNetAssembly : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file to examine.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the file is a .NET assembly; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isNetAssembly As Boolean = IsNetAssembly("C:\Assembly.dll")
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />