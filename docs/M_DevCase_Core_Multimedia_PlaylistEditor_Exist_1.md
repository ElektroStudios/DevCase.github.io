# PlaylistEditor.Exist Method (String)
 

Determines whether the specified track exists in the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Exist(
	string filepath
)
```

**VB**<br />
``` VB
Public Function Exist ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim filepath As String
Dim returnValue As Boolean

returnValue = instance.Exist(filepath)
```

**C++**<br />
``` C++
public:
bool Exist(
	String^ filepath
)
```

**F#**<br />
``` F#
member Exist : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The track filepath.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the track already exists in the playlist, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Exist">Exist Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />