# ReflectionUtil.GetCLRVersion Method 
 

Gets the CLR runtime version on which the specified assembly runs on.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Version GetCLRVersion(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetCLRVersion ( 
	filepath As String
) As Version
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Version

returnValue = ReflectionUtil.GetCLRVersion(filepath)
```

**C++**<br />
``` C++
public:
static Version^ GetCLRVersion(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetCLRVersion : 
        filepath : string -> Version 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: Version<br />The CLR runtime version.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim clrVersion As Version = GetCLRVersion("C:\Assembly.dll")
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />