# RecycleBinUtil.GetLastRecycledFolder Method 
 

Gets the last recycled folder that is inside the recycle bin of an specific drive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ShellFolder GetLastRecycledFolder(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetLastRecycledFolder ( 
	driveLetter As Char
) As ShellFolder
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As ShellFolder

returnValue = RecycleBinUtil.GetLastRecycledFolder(driveLetter)
```

**C++**<br />
``` C++
public:
static ShellFolder^ GetLastRecycledFolder(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetLastRecycledFolder : 
        driveLetter : char -> ShellFolder 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The recycle bin drive letter.</dd></dl>

#### Return Value
Type: ShellFolder<br />The last recycled folder that is inside the recycle bin of an specific drive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />