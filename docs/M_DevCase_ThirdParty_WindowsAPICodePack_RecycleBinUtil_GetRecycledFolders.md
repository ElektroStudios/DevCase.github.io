# RecycleBinUtil.GetRecycledFolders Method 
 

Gets all the recycled folders that are inside the recycle bin of an specific drive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<ShellFolder> GetRecycledFolders(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetRecycledFolders ( 
	driveLetter As Char
) As IEnumerable(Of ShellFolder)
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As IEnumerable(Of ShellFolder)

returnValue = RecycleBinUtil.GetRecycledFolders(driveLetter)
```

**C++**<br />
``` C++
public:
static IEnumerable<ShellFolder^>^ GetRecycledFolders(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetRecycledFolders : 
        driveLetter : char -> IEnumerable<ShellFolder> 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The recycle bin drive letter.</dd></dl>

#### Return Value
Type: IEnumerable(ShellFolder)<br />All the recycled folders that are inside the recycle bin of an specific drive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />