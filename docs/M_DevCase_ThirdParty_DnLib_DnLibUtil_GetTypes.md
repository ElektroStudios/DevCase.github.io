# DnLibUtil.GetTypes Method (ModuleDefMD)
 

Gets all the Types defined (including nested Types) inside a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<TypeDef> GetTypes(
	ModuleDefMD assembly
)
```

**VB**<br />
``` VB
Public Shared Function GetTypes ( 
	assembly As ModuleDefMD
) As ReadOnlyCollection(Of TypeDef)
```

**VB Usage**<br />
``` VB Usage
Dim assembly As ModuleDefMD
Dim returnValue As ReadOnlyCollection(Of TypeDef)

returnValue = DnLibUtil.GetTypes(assembly)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<TypeDef^>^ GetTypes(
	ModuleDefMD^ assembly
)
```

**F#**<br />
``` F#
static member GetTypes : 
        assembly : ModuleDefMD -> ReadOnlyCollection<TypeDef> 

```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: ModuleDefMD<br />The assembly.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(TypeDef)<br />A ReadOnlyCollection(T) containing the Types defined (including nested Types) inside a .NET assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assembly As ModuleDefMD = LoadAssembly("C:\Application.exe")
Dim types As ReadOnlyCollection(Of TypeDef) = GetTypes(assembly)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_GetTypes">GetTypes Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />