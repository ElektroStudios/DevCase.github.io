# Archiver Constructor (OutArchiveFormat, FileInfo)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Archiver(
	OutArchiveFormat archiveFormat,
	FileInfo sevenZipLibraryFile
)
```

**VB**<br />
``` VB
Public Sub New ( 
	archiveFormat As OutArchiveFormat,
	sevenZipLibraryFile As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim archiveFormat As OutArchiveFormat
Dim sevenZipLibraryFile As FileInfo

Dim instance As New Archiver(archiveFormat, 
	sevenZipLibraryFile)
```

**C++**<br />
``` C++
public:
Archiver(
	OutArchiveFormat archiveFormat, 
	FileInfo^ sevenZipLibraryFile
)
```

**F#**<br />
``` F#
new : 
        archiveFormat : OutArchiveFormat * 
        sevenZipLibraryFile : FileInfo -> Archiver
```


#### Parameters
&nbsp;<dl><dt>archiveFormat</dt><dd>Type: OutArchiveFormat<br />The archive format (7zip, GZip, etc).</dd><dt>sevenZipLibraryFile</dt><dd>Type: System.IO.FileInfo<br />The `7z.dll` file.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver__ctor">Archiver Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />