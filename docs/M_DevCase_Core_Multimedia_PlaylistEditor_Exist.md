# PlaylistEditor.Exist Method (Int32)
 

Determines whether the specified track exists in the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Exist(
	int trackIndex
)
```

**VB**<br />
``` VB
Public Function Exist ( 
	trackIndex As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim trackIndex As Integer
Dim returnValue As Boolean

returnValue = instance.Exist(trackIndex)
```

**C++**<br />
``` C++
public:
bool Exist(
	int trackIndex
)
```

**F#**<br />
``` F#
member Exist : 
        trackIndex : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>trackIndex</dt><dd>Type: System.Int32<br />The track index.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the track already exists in the playlist, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IndexOutOfRangeException</td><td>TrackIndex should be greater than 0.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Exist">Exist Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />