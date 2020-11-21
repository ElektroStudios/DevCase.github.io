# PlaylistEditor.Set Method (Int32, PlaylistTrackInfo)
 

Sets the extended track info of the specified track.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Set(
	int trackIndex,
	PlaylistTrackInfo trackInfo
)
```

**VB**<br />
``` VB
Public Sub Set ( 
	trackIndex As Integer,
	trackInfo As PlaylistTrackInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim trackIndex As Integer
Dim trackInfo As PlaylistTrackInfo

instance.Set(trackIndex, trackInfo)
```

**C++**<br />
``` C++
public:
void Set(
	int trackIndex, 
	PlaylistTrackInfo^ trackInfo
)
```

**F#**<br />
``` F#
member Set : 
        trackIndex : int * 
        trackInfo : PlaylistTrackInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>trackIndex</dt><dd>Type: System.Int32<br />The track index to set its extended track info.</dd><dt>trackInfo</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">DevCase.Core.Multimedia.PlaylistTrackInfo</a><br />A <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a> instance containing the extended info to set.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IndexOutOfRangeException</td><td>TrackIndex is out of range</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Set">Set Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />