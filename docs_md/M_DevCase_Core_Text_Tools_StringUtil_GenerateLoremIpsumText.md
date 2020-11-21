# StringUtil.GenerateLoremIpsumText Method 
 

Generates a random 'Lorem Ipsum' paragraph.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GenerateLoremIpsumText(
	int numberOfParagraphs,
	bool htmlFormatting
)
```

**VB**<br />
``` VB
Public Shared Function GenerateLoremIpsumText ( 
	numberOfParagraphs As Integer,
	htmlFormatting As Boolean
) As String
```

**VB Usage**<br />
``` VB Usage
Dim numberOfParagraphs As Integer
Dim htmlFormatting As Boolean
Dim returnValue As String

returnValue = StringUtil.GenerateLoremIpsumText(numberOfParagraphs, 
	htmlFormatting)
```

**C++**<br />
``` C++
public:
static String^ GenerateLoremIpsumText(
	int numberOfParagraphs, 
	bool htmlFormatting
)
```

**F#**<br />
``` F#
static member GenerateLoremIpsumText : 
        numberOfParagraphs : int * 
        htmlFormatting : bool -> string 

```


#### Parameters
&nbsp;<dl><dt>numberOfParagraphs</dt><dd>Type: System.Int32<br />Specifies the number of paragraphs to generate.</dd><dt>htmlFormatting</dt><dd>Type: System.Boolean<br />Specifies whether or not to format paragraphs for HTML.</dd></dl>

#### Return Value
Type: String<br />The resulting 'Lorem Ipsum' paragraph(s).

## Remarks
Wikipedia article: <a href="https://en.wikipedia.org/wiki/Lorem_ipsum" target="_blank">https://en.wikipedia.org/wiki/Lorem_ipsum</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim loremIpsum As String = GenerateLoremIpsumText(numberOfParagraphs:=4, htmlFormatting:=False)
Console.WriteLine(loremIpsum)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil">StringUtil Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />