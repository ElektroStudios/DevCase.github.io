# PlaylistEditor.Add Method (String, Boolean)
 

Adds a new track entry in the playlist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	string filepath,
	bool allowDuplicate = false
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	filepath As String,
	Optional allowDuplicate As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim filepath As String
Dim allowDuplicate As Boolean

instance.Add(filepath, allowDuplicate)
```

**C++**<br />
``` C++
public:
void Add(
	String^ filepath, 
	bool allowDuplicate = false
)
```

**F#**<br />
``` F#
member Add : 
        filepath : string * 
        ?allowDuplicate : bool 
(* Defaults:
        let _allowDuplicate = defaultArg allowDuplicate false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The track path to add.</dd><dt>allowDuplicate (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic) an exception will be thrown if the track already exists in the playlist.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>The TrackPath already exist in the playlist.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Add">Add Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />