# LyricLine Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Multimedia_LyricLine">LyricLine</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LyricLine(
	int index,
	int startTime,
	int endTime,
	string text
)
```

**VB**<br />
``` VB
Public Sub New ( 
	index As Integer,
	startTime As Integer,
	endTime As Integer,
	text As String
)
```

**VB Usage**<br />
``` VB Usage
Dim index As Integer
Dim startTime As Integer
Dim endTime As Integer
Dim text As String

Dim instance As New LyricLine(index, startTime, 
	endTime, text)
```

**C++**<br />
``` C++
public:
LyricLine(
	int index, 
	int startTime, 
	int endTime, 
	String^ text
)
```

**F#**<br />
``` F#
new : 
        index : int * 
        startTime : int * 
        endTime : int * 
        text : string -> LyricLine
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />\[Missing <param name="index"/> documentation for "M:DevCase.Core.Multimedia.LyricLine.#ctor(System.Int32,System.Int32,System.Int32,System.String)"\]</dd><dt>startTime</dt><dd>Type: System.Int32<br />The ending lyric time, in milliseconds.</dd><dt>endTime</dt><dd>Type: System.Int32<br />The ending lyric time, in milliseconds.</dd><dt>text</dt><dd>Type: System.String<br />The lyric text.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_LyricLine">LyricLine Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />