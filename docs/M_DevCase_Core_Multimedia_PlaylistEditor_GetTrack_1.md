# PlaylistEditor.GetTrack Method (String)
 

Gets the extended track information (if any) of the specified track in the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PlaylistTrackInfo GetTrack(
	string filepath
)
```

**VB**<br />
``` VB
Public Function GetTrack ( 
	filepath As String
) As PlaylistTrackInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim filepath As String
Dim returnValue As PlaylistTrackInfo

returnValue = instance.GetTrack(filepath)
```

**C++**<br />
``` C++
public:
PlaylistTrackInfo^ GetTrack(
	String^ filepath
)
```

**F#**<br />
``` F#
member GetTrack : 
        filepath : string -> PlaylistTrackInfo 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The track path.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a><br />If the track contains extended iformation, the return value is a <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a> instance containing the track info. 

 Otherwise, the return value is an emptiness <a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a> instance.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_GetTrack">GetTrack Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />