# RecycleBinUtil.Clean Method 
 

Cleans the Recycle Bin of an specific Drive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Clean(
	char driveLetter,
	RecycleFlags flags = 
)
```

**VB**<br />
``` VB
Public Shared Function Clean ( 
	driveLetter As Char,
	Optional flags As RecycleFlags = 
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim flags As RecycleFlags
Dim returnValue As Boolean

returnValue = RecycleBinUtil.Clean(driveLetter, 
	flags)
```

**C++**<br />
``` C++
public:
static bool Clean(
	wchar_t driveLetter, 
	RecycleFlags flags = 
)
```

**F#**<br />
``` F#
static member Clean : 
        driveLetter : char * 
        ?flags : RecycleFlags 
(* Defaults:
        let _flags = defaultArg flags 
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The recycle bin drive letter. If this parameter is a null reference (`Nothing` in Visual Basic) then it cleans all the Recycle Bins.</dd><dt>flags (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_RecycleFlags">DevCase.Core.Shell.RecycleFlags</a><br />The recycle bin behavior.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />