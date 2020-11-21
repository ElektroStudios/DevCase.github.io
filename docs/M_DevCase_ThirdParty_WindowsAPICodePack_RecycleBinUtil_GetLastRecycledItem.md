# RecycleBinUtil.GetLastRecycledItem Method 
 

Gets the last recycled item that is inside the recycle bin of an specific drive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ShellObject GetLastRecycledItem(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetLastRecycledItem ( 
	driveLetter As Char
) As ShellObject
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As ShellObject

returnValue = RecycleBinUtil.GetLastRecycledItem(driveLetter)
```

**C++**<br />
``` C++
public:
static ShellObject^ GetLastRecycledItem(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetLastRecycledItem : 
        driveLetter : char -> ShellObject 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The recycle bin drive letter.</dd></dl>

#### Return Value
Type: ShellObject<br />The last recycled item that is inside the recycle bin of an specific drive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />