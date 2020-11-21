# PlaylistEditor.GetTrack Method (Int32)
 

Gets the track path and its extended track information (if any) of the specified track index in the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PlaylistTrackInfo GetTrack(
	int trackIndex
)
```

**VB**<br />
``` VB
Public Function GetTrack ( 
	trackIndex As Integer
) As PlaylistTrackInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim trackIndex As Integer
Dim returnValue As PlaylistTrackInfo

returnValue = instance.GetTrack(trackIndex)
```

**C++**<br />
``` C++
public:
PlaylistTrackInfo^ GetTrack(
	int trackIndex
)
```

**F#**<br />
``` F#
member GetTrack : 
        trackIndex : int -> PlaylistTrackInfo 

```


#### Parameters
&nbsp;<dl><dt>trackIndex</dt><dd>Type: System.Int32<br />The track index.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a><br />If the track index exist, the return value is a <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a> instance containing the track path and its extended info (if any). Otherwise, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_GetTrack">GetTrack Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />