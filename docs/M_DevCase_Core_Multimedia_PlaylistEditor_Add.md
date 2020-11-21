# PlaylistEditor.Add Method (PlaylistTrackInfo, Boolean)
 

Adds a new track entry in the playlist, with extended track information.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	PlaylistTrackInfo trackInfo,
	bool allowDuplicate = false
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	trackInfo As PlaylistTrackInfo,
	Optional allowDuplicate As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim trackInfo As PlaylistTrackInfo
Dim allowDuplicate As Boolean

instance.Add(trackInfo, allowDuplicate)
```

**C++**<br />
``` C++
public:
void Add(
	PlaylistTrackInfo^ trackInfo, 
	bool allowDuplicate = false
)
```

**F#**<br />
``` F#
member Add : 
        trackInfo : PlaylistTrackInfo * 
        ?allowDuplicate : bool 
(* Defaults:
        let _allowDuplicate = defaultArg allowDuplicate false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>trackInfo</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">DevCase.Core.Multimedia.PlaylistTrackInfo</a><br />A <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a> instance containing the extended track information.</dd><dt>allowDuplicate (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="allowDuplicate"/> documentation for "M:DevCase.Core.Multimedia.PlaylistEditor.Add(DevCase.Core.Multimedia.PlaylistTrackInfo,System.Boolean)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Add">Add Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />