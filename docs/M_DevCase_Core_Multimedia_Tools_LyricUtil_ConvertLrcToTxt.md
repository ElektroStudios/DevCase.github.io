# LyricUtil.ConvertLrcToTxt Method 
 

Converts a LRC lyric string to plain text.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ConvertLrcToTxt(
	string lrc
)
```

**VB**<br />
``` VB
Public Shared Function ConvertLrcToTxt ( 
	lrc As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim lrc As String
Dim returnValue As String

returnValue = LyricUtil.ConvertLrcToTxt(lrc)
```

**C++**<br />
``` C++
public:
static String^ ConvertLrcToTxt(
	String^ lrc
)
```

**F#**<br />
``` F#
static member ConvertLrcToTxt : 
        lrc : string -> string 

```


#### Parameters
&nbsp;<dl><dt>lrc</dt><dd>Type: System.String<br />The LRC lyric string.</dd></dl>

#### Return Value
Type: String<br />The resulting string of the conversion.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lrc As String = File.ReadAllText("C:\File.lrc", Encoding.Default)
Dim txt As String = ConvertLrcToTxt(lrc)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_LyricUtil">LyricUtil Class</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />