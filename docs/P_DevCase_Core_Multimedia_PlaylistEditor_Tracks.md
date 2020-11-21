# PlaylistEditor.Tracks Property 
 

Gets all the tracks and their extended track information (if any) in the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<PlaylistTrackInfo> Tracks { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Tracks As ReadOnlyCollection(Of PlaylistTrackInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim value As ReadOnlyCollection(Of PlaylistTrackInfo)

value = instance.Tracks

```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<PlaylistTrackInfo^>^ Tracks {
	ReadOnlyCollection<PlaylistTrackInfo^>^ get ();
}
```

**F#**<br />
``` F#
member Tracks : ReadOnlyCollection<PlaylistTrackInfo> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo</a>)<br />A List(T) object containing the track entries and its extended info (if any).

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />