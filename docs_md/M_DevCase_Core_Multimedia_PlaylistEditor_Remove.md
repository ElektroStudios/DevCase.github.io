# PlaylistEditor.Remove Method (Int32)
 

Removes the specified track entry from the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Remove(
	int trackIndex
)
```

**VB**<br />
``` VB
Public Sub Remove ( 
	trackIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim trackIndex As Integer

instance.Remove(trackIndex)
```

**C++**<br />
``` C++
public:
void Remove(
	int trackIndex
)
```

**F#**<br />
``` F#
member Remove : 
        trackIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>trackIndex</dt><dd>Type: System.Int32<br />The track index to remove it's entry.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IndexOutOfRangeException</td><td>TrackIndex is out of range</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Remove">Remove Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />