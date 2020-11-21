# PlaylistEditor.Set Method (String, PlaylistTrackInfo)
 

Sets the extended track info of the specified track.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Set(
	string filepath,
	PlaylistTrackInfo trackInfo
)
```

**VB**<br />
``` VB
Public Sub Set ( 
	filepath As String,
	trackInfo As PlaylistTrackInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim filepath As String
Dim trackInfo As PlaylistTrackInfo

instance.Set(filepath, trackInfo)
```

**C++**<br />
``` C++
public:
void Set(
	String^ filepath, 
	PlaylistTrackInfo^ trackInfo
)
```

**F#**<br />
``` F#
member Set : 
        filepath : string * 
        trackInfo : PlaylistTrackInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The track path to set its extended track info.</dd><dt>trackInfo</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">DevCase.Core.Multimedia.PlaylistTrackInfo</a><br />A <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a> instance containing the extended info to set.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>The TrackPath was not found in the playlist.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Set">Set Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />