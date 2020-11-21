# TransformUtil.Html2Rtf Method 
 

Converts HTML text to RTF.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Nasosoft">DevCase.ThirdParty.Nasosoft</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Html2Rtf(
	string htmlText,
	Encoding textEncoding = null
)
```

**VB**<br />
``` VB
Public Shared Function Html2Rtf ( 
	htmlText As String,
	Optional textEncoding As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim htmlText As String
Dim textEncoding As Encoding
Dim returnValue As String

returnValue = TransformUtil.Html2Rtf(htmlText, 
	textEncoding)
```

**C++**<br />
``` C++
public:
static String^ Html2Rtf(
	String^ htmlText, 
	Encoding^ textEncoding = nullptr
)
```

**F#**<br />
``` F#
static member Html2Rtf : 
        htmlText : string * 
        ?textEncoding : Encoding 
(* Defaults:
        let _textEncoding = defaultArg textEncoding null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>htmlText</dt><dd>Type: System.String<br />Indicates the HTML text.</dd><dt>textEncoding (Optional)</dt><dd>Type: System.Text.Encoding<br />Indicates the text encoding.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rtf As String = Html2Rtf(File.ReadAllText("C:\File.html"))
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Nasosoft_TransformUtil">TransformUtil Class</a><br /><a href="N_DevCase_ThirdParty_Nasosoft">DevCase.ThirdParty.Nasosoft Namespace</a><br />