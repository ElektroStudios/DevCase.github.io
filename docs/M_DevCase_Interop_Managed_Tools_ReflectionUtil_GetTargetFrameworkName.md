# ReflectionUtil.GetTargetFrameworkName Method 
 

Gets the display name of the .NET Framework version on which the source assembly was compiled.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetTargetFrameworkName(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetTargetFrameworkName ( 
	filepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As String

returnValue = ReflectionUtil.GetTargetFrameworkName(filepath)
```

**C++**<br />
``` C++
public:
static String^ GetTargetFrameworkName(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetTargetFrameworkName : 
        filepath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: String<br />The display name of the .NET Framework version on which the source assembly was compiled.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim targetFrameworkName As Version = GetTargetFrameworkName("C:\Assembly.dll")
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />