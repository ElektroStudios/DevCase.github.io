# ArchiveInfo Constructor (String, String)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ArchiveInfo(
	string sevenZipLibraryFilepath,
	string archivePath
)
```

**VB**<br />
``` VB
Public Sub New ( 
	sevenZipLibraryFilepath As String,
	archivePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sevenZipLibraryFilepath As String
Dim archivePath As String

Dim instance As New ArchiveInfo(sevenZipLibraryFilepath, 
	archivePath)
```

**C++**<br />
``` C++
public:
ArchiveInfo(
	String^ sevenZipLibraryFilepath, 
	String^ archivePath
)
```

**F#**<br />
``` F#
new : 
        sevenZipLibraryFilepath : string * 
        archivePath : string -> ArchiveInfo
```


#### Parameters
&nbsp;<dl><dt>sevenZipLibraryFilepath</dt><dd>Type: System.String<br />The full path to `7z.dll` file.</dd><dt>archivePath</dt><dd>Type: System.String<br />The full path of the compressed archive.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo__ctor">ArchiveInfo Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />