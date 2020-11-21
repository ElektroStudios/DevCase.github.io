# LyricFile Constructor (String)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SubtitleWorkshop_LyricFile">LyricFile</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LyricFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String

Dim instance As New LyricFile(filepath)
```

**C++**<br />
``` C++
public:
LyricFile(
	String^ filepath
)
```

**F#**<br />
``` F#
new : 
        filepath : string -> LyricFile
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The full path of the lyric file to load.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File not found.</td></tr><tr><td>Exception</td><td>Error trying to open the specified file. Check the file and/or the SubtitleAPI dll.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SubtitleWorkshop_LyricFile">LyricFile Class</a><br /><a href="Overload_DevCase_ThirdParty_SubtitleWorkshop_LyricFile__ctor">LyricFile Overload</a><br /><a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />