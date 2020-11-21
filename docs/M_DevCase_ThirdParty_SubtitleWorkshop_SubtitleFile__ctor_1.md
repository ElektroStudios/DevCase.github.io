# SubtitleFile Constructor (String, Single)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile">SubtitleFile</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SubtitleFile(
	string filepath,
	float fps
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filepath As String,
	fps As Single
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim fps As Single

Dim instance As New SubtitleFile(filepath, 
	fps)
```

**C++**<br />
``` C++
public:
SubtitleFile(
	String^ filepath, 
	float fps
)
```

**F#**<br />
``` F#
new : 
        filepath : string * 
        fps : float32 -> SubtitleFile
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The full path of the subtitle file to load.</dd><dt>fps</dt><dd>Type: System.Single<br />The FPS of the subtitle.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File not found.</td></tr><tr><td>Exception</td><td>Error trying to open the specified file. Check the file and/or the SubtitleAPI dll.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile">SubtitleFile Class</a><br /><a href="Overload_DevCase_ThirdParty_SubtitleWorkshop_SubtitleFile__ctor">SubtitleFile Overload</a><br /><a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />