# RecycleBinUtil.GetRecycledFiles Method 
 

Gets all the recycled files that are inside the recycle bin of an specific drive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<ShellFile> GetRecycledFiles(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetRecycledFiles ( 
	driveLetter As Char
) As IEnumerable(Of ShellFile)
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As IEnumerable(Of ShellFile)

returnValue = RecycleBinUtil.GetRecycledFiles(driveLetter)
```

**C++**<br />
``` C++
public:
static IEnumerable<ShellFile^>^ GetRecycledFiles(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetRecycledFiles : 
        driveLetter : char -> IEnumerable<ShellFile> 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The recycle bin drive letter.</dd></dl>

#### Return Value
Type: IEnumerable(ShellFile)<br />All the recycled files that are inside the recycle bin of an specific drive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />