# TransformUtil.Rtf2Html Method 
 

Converts RTF text to HTML.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Nasosoft">DevCase.ThirdParty.Nasosoft</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Rtf2Html(
	string rtfText,
	Encoding textEncoding = null
)
```

**VB**<br />
``` VB
Public Shared Function Rtf2Html ( 
	rtfText As String,
	Optional textEncoding As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim rtfText As String
Dim textEncoding As Encoding
Dim returnValue As String

returnValue = TransformUtil.Rtf2Html(rtfText, 
	textEncoding)
```

**C++**<br />
``` C++
public:
static String^ Rtf2Html(
	String^ rtfText, 
	Encoding^ textEncoding = nullptr
)
```

**F#**<br />
``` F#
static member Rtf2Html : 
        rtfText : string * 
        ?textEncoding : Encoding 
(* Defaults:
        let _textEncoding = defaultArg textEncoding null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>rtfText</dt><dd>Type: System.String<br />Indicates the RTF text.</dd><dt>textEncoding (Optional)</dt><dd>Type: System.Text.Encoding<br />Indicates the text encoding.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rtf As String = "{\rtf1\ansi\fbidis\ansicpg1252\deff0{\fonttbl{\f0\fswiss\fcharset0 Times New Roman;}{\f1\fswiss\fcharset2 Symbol;}}{\colortbl;\red192\green192\blue192;}\viewkind5\viewscale100{\*\bkmkstart BM_BEGIN}\pard\plain\f0{Hello World!}}"

Dim html As String = Rtf2Html(rtf)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Nasosoft_TransformUtil">TransformUtil Class</a><br /><a href="N_DevCase_ThirdParty_Nasosoft">DevCase.ThirdParty.Nasosoft Namespace</a><br />