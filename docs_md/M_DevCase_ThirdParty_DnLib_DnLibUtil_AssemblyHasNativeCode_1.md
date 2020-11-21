# DnLibUtil.AssemblyHasNativeCode Method (String)
 

Determines whether a .NET Assembly has native code (C++/CLI).

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AssemblyHasNativeCode(
	string assemblyPath
)
```

**VB**<br />
``` VB
Public Shared Function AssemblyHasNativeCode ( 
	assemblyPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim assemblyPath As String
Dim returnValue As Boolean

returnValue = DnLibUtil.AssemblyHasNativeCode(assemblyPath)
```

**C++**<br />
``` C++
public:
static bool AssemblyHasNativeCode(
	String^ assemblyPath
)
```

**F#**<br />
``` F#
static member AssemblyHasNativeCode : 
        assemblyPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>assemblyPath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the aasembly contains native code; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim IsNativeCoded As Boolean = AssemblyHasNativeCode("C:\Application.exe")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_AssemblyHasNativeCode">AssemblyHasNativeCode Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />