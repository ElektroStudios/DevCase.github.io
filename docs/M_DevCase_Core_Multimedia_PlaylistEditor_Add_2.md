# PlaylistEditor.Add Method (String, String, TimeSpan, Boolean)
 

Adds a new track entry in the playlist, with extended track information.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	string filepath,
	string title,
	TimeSpan length,
	bool allowDuplicate = false
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	filepath As String,
	title As String,
	length As TimeSpan,
	Optional allowDuplicate As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
Dim filepath As String
Dim title As String
Dim length As TimeSpan
Dim allowDuplicate As Boolean

instance.Add(filepath, title, length, allowDuplicate)
```

**C++**<br />
``` C++
public:
void Add(
	String^ filepath, 
	String^ title, 
	TimeSpan length, 
	bool allowDuplicate = false
)
```

**F#**<br />
``` F#
member Add : 
        filepath : string * 
        title : string * 
        length : TimeSpan * 
        ?allowDuplicate : bool 
(* Defaults:
        let _allowDuplicate = defaultArg allowDuplicate false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The track to add.</dd><dt>title</dt><dd>Type: System.String<br />The track title.</dd><dt>length</dt><dd>Type: System.TimeSpan<br />The track length.</dd><dt>allowDuplicate (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="allowDuplicate"/> documentation for "M:DevCase.Core.Multimedia.PlaylistEditor.Add(System.String,System.String,System.TimeSpan,System.Boolean)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor Class</a><br /><a href="Overload_DevCase_Core_Multimedia_PlaylistEditor_Add">Add Overload</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />