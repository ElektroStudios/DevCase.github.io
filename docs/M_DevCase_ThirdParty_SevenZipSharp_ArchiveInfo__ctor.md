# ArchiveInfo Constructor (FileInfo, FileInfo)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ArchiveInfo(
	FileInfo sevenZipLibraryFile,
	FileInfo archive
)
```

**VB**<br />
``` VB
Public Sub New ( 
	sevenZipLibraryFile As FileInfo,
	archive As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim sevenZipLibraryFile As FileInfo
Dim archive As FileInfo

Dim instance As New ArchiveInfo(sevenZipLibraryFile, 
	archive)
```

**C++**<br />
``` C++
public:
ArchiveInfo(
	FileInfo^ sevenZipLibraryFile, 
	FileInfo^ archive
)
```

**F#**<br />
``` F#
new : 
        sevenZipLibraryFile : FileInfo * 
        archive : FileInfo -> ArchiveInfo
```


#### Parameters
&nbsp;<dl><dt>sevenZipLibraryFile</dt><dd>Type: System.IO.FileInfo<br />The `7z.dll` file.</dd><dt>archive</dt><dd>Type: System.IO.FileInfo<br />The compressed archive.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo__ctor">ArchiveInfo Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />