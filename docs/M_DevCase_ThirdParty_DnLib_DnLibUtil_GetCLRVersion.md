# DnLibUtil.GetCLRVersion Method (ModuleDefMD)
 

Gets the CLR runtime version of a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetCLRVersion(
	ModuleDefMD assembly
)
```

**VB**<br />
``` VB
Public Shared Function GetCLRVersion ( 
	assembly As ModuleDefMD
) As String
```

**VB Usage**<br />
``` VB Usage
Dim assembly As ModuleDefMD
Dim returnValue As String

returnValue = DnLibUtil.GetCLRVersion(assembly)
```

**C++**<br />
``` C++
public:
static String^ GetCLRVersion(
	ModuleDefMD^ assembly
)
```

**F#**<br />
``` F#
static member GetCLRVersion : 
        assembly : ModuleDefMD -> string 

```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: ModuleDefMD<br />The assembly.</dd></dl>

#### Return Value
Type: String<br />The CLR runtime version of a .NET assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assembly As ModuleDefMD = LoadAssembly("C:\Application.exe")
Dim clrVersion As String = GetRuntimeVersion(assembly)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_GetCLRVersion">GetCLRVersion Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />