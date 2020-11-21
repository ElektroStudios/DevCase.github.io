# PlaylistEditor Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PlaylistEditor(
	string playlistFile,
	PlaylistType playlistType,
	bool append,
	Encoding fileEncoding = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	playlistFile As String,
	playlistType As PlaylistType,
	append As Boolean,
	Optional fileEncoding As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim playlistFile As String
Dim playlistType As PlaylistType
Dim append As Boolean
Dim fileEncoding As Encoding

Dim instance As New PlaylistEditor(playlistFile, 
	playlistType, append, fileEncoding)
```

**C++**<br />
``` C++
public:
PlaylistEditor(
	String^ playlistFile, 
	PlaylistType playlistType, 
	bool append, 
	Encoding^ fileEncoding = nullptr
)
```

**F#**<br />
``` F#
new : 
        playlistFile : string * 
        playlistType : PlaylistType * 
        append : bool * 
        ?fileEncoding : Encoding 
(* Defaults:
        let _fileEncoding = defaultArg fileEncoding null
*)
-> PlaylistEditor
```


#### Parameters
&nbsp;<dl><dt>playlistFile</dt><dd>Type: System.String<br />The playlist filepath.</dd><dt>playlistType</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_PlaylistType">DevCase.Core.Multimedia.PlaylistType</a><br />The type of the playlist.</dd><dt>append</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the <a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor</a> instance will assume that the playlist file already exist, and will append any new entries in the existing file. 

 If set to `false` (`False` in Visual Basic), the <a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor</a> instance will assume that the playlist file does not exist, and will create the file.</dd><dt>fileEncoding (Optional)</dt><dd>Type: System.Text.Encoding<br />Optionally indicates the file encoding to write/read the playlist content. 

 The default value is Default</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />