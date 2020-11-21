# DnLibUtil.LoadAssembly Method 
 

Loads an Assembly into a ModuleDefMD instance.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ModuleDefMD LoadAssembly(
	string assemblyPath
)
```

**VB**<br />
``` VB
Public Shared Function LoadAssembly ( 
	assemblyPath As String
) As ModuleDefMD
```

**VB Usage**<br />
``` VB Usage
Dim assemblyPath As String
Dim returnValue As ModuleDefMD

returnValue = DnLibUtil.LoadAssembly(assemblyPath)
```

**C++**<br />
``` C++
public:
static ModuleDefMD^ LoadAssembly(
	String^ assemblyPath
)
```

**F#**<br />
``` F#
static member LoadAssembly : 
        assemblyPath : string -> ModuleDefMD 

```


#### Parameters
&nbsp;<dl><dt>assemblyPath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: ModuleDefMD<br />ModuleDefMD.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assembly As ModuleDefMD = LoadAssembly("C:\Application.exe")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />