# Archiver Constructor (OutArchiveFormat, String)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Archiver(
	OutArchiveFormat archiveFormat,
	string sevenZipLibraryFilepath
)
```

**VB**<br />
``` VB
Public Sub New ( 
	archiveFormat As OutArchiveFormat,
	sevenZipLibraryFilepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim archiveFormat As OutArchiveFormat
Dim sevenZipLibraryFilepath As String

Dim instance As New Archiver(archiveFormat, 
	sevenZipLibraryFilepath)
```

**C++**<br />
``` C++
public:
Archiver(
	OutArchiveFormat archiveFormat, 
	String^ sevenZipLibraryFilepath
)
```

**F#**<br />
``` F#
new : 
        archiveFormat : OutArchiveFormat * 
        sevenZipLibraryFilepath : string -> Archiver
```


#### Parameters
&nbsp;<dl><dt>archiveFormat</dt><dd>Type: OutArchiveFormat<br />The archive format (7zip, GZip, etc).</dd><dt>sevenZipLibraryFilepath</dt><dd>Type: System.String<br />The full path to `7z.dll` file.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver__ctor">Archiver Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />