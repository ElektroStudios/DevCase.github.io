# RecycleBinUtil.GetBinSize Method 
 

Gets the accumulated size (in bytes) of the recycle bin of an specific drive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long GetBinSize(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetBinSize ( 
	driveLetter As Char
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As Long

returnValue = RecycleBinUtil.GetBinSize(driveLetter)
```

**C++**<br />
``` C++
public:
static long long GetBinSize(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetBinSize : 
        driveLetter : char -> int64 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The recycle bin drive letter.</dd></dl>

#### Return Value
Type: Int64<br />The accumulated size (in bytes) of the recycle bin of an specific drive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />