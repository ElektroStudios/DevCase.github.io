# LyricFile Constructor (FileInfo)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SubtitleWorkshop_LyricFile">LyricFile</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LyricFile(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Sub New ( 
	file As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo

Dim instance As New LyricFile(file)
```

**C++**<br />
``` C++
public:
LyricFile(
	FileInfo^ file
)
```

**F#**<br />
``` F#
new : 
        file : FileInfo -> LyricFile
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The lyric file to load.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File not found.</td></tr><tr><td>Exception</td><td>Error trying to open the specified file. Check the file and/or the SubtitleAPI dll.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SubtitleWorkshop_LyricFile">LyricFile Class</a><br /><a href="Overload_DevCase_ThirdParty_SubtitleWorkshop_LyricFile__ctor">LyricFile Overload</a><br /><a href="N_DevCase_ThirdParty_SubtitleWorkshop">DevCase.ThirdParty.SubtitleWorkshop Namespace</a><br />