# DnLibUtil.AssemblyHasNativeCode Method (ModuleDef)
 

Determines whether a .NET assembly has native code (C++/CLI).

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AssemblyHasNativeCode(
	ModuleDef assembly
)
```

**VB**<br />
``` VB
Public Shared Function AssemblyHasNativeCode ( 
	assembly As ModuleDef
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim assembly As ModuleDef
Dim returnValue As Boolean

returnValue = DnLibUtil.AssemblyHasNativeCode(assembly)
```

**C++**<br />
``` C++
public:
static bool AssemblyHasNativeCode(
	ModuleDef^ assembly
)
```

**F#**<br />
``` F#
static member AssemblyHasNativeCode : 
        assembly : ModuleDef -> bool 

```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: ModuleDef<br />The assembly.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the aasembly contains native code; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assembly As ModuleDefMD = LoadAssembly("C:\Application.exe")
Dim IsNativeCoded As Boolean = AssemblyHasNativeCode(assembly)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_AssemblyHasNativeCode">AssemblyHasNativeCode Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />