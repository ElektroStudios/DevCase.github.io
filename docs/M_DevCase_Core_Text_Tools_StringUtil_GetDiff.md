# StringUtil.GetDiff Method 
 

Gets the character differences between two strings.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SortedDictionary<int, CharDiff> GetDiff(
	string originalText,
	string currentText
)
```

**VB**<br />
``` VB
Public Shared Function GetDiff ( 
	originalText As String,
	currentText As String
) As SortedDictionary(Of Integer, CharDiff)
```

**VB Usage**<br />
``` VB Usage
Dim originalText As String
Dim currentText As String
Dim returnValue As SortedDictionary(Of Integer, CharDiff)

returnValue = StringUtil.GetDiff(originalText, 
	currentText)
```

**C++**<br />
``` C++
public:
static SortedDictionary<int, CharDiff>^ GetDiff(
	String^ originalText, 
	String^ currentText
)
```

**F#**<br />
``` F#
static member GetDiff : 
        originalText : string * 
        currentText : string -> SortedDictionary<int, CharDiff> 

```


#### Parameters
&nbsp;<dl><dt>originalText</dt><dd>Type: System.String<br />The original text to compare.</dd><dt>currentText</dt><dd>Type: System.String<br />The current text to compare with *originalText*.</dd></dl>

#### Return Value
Type: SortedDictionary(Int32, <a href="T_DevCase_Core_Text_CharDiff">CharDiff</a>)<br />An SortedDictionary(TKey, TValue) that contains the difference state of all the characters in *currentText*.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />