# DnLibUtil.GetCLRVersion Method (String)
 

Gets the CLR runtime version of a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetCLRVersion(
	string assemblyPath
)
```

**VB**<br />
``` VB
Public Shared Function GetCLRVersion ( 
	assemblyPath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim assemblyPath As String
Dim returnValue As String

returnValue = DnLibUtil.GetCLRVersion(assemblyPath)
```

**C++**<br />
``` C++
public:
static String^ GetCLRVersion(
	String^ assemblyPath
)
```

**F#**<br />
``` F#
static member GetCLRVersion : 
        assemblyPath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>assemblyPath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: String<br />The CLR runtime version of a .NET assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim clrVersion As String = GetRuntimeVersion("C:\Application.exe")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_GetCLRVersion">GetCLRVersion Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />