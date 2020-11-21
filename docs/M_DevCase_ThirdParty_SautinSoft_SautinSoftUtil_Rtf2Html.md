# SautinSoftUtil.Rtf2Html Method 
 

Converts RtF to HtML.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SautinSoft">DevCase.ThirdParty.SautinSoft</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Rtf2Html(
	string rtfText,
	eOutputFormat outputFormat = eOutputFormat.XHTML_10,
	eEncoding textEncoding = eEncoding.UTF_8,
	bool saveImagesToDisk = false,
	string imageFolder = "C:\"
)
```

**VB**<br />
``` VB
Public Shared Function Rtf2Html ( 
	rtfText As String,
	Optional outputFormat As eOutputFormat = eOutputFormat.XHTML_10,
	Optional textEncoding As eEncoding = eEncoding.UTF_8,
	Optional saveImagesToDisk As Boolean = false,
	Optional imageFolder As String = "C:\"
) As String
```

**VB Usage**<br />
``` VB Usage
Dim rtfText As String
Dim outputFormat As eOutputFormat
Dim textEncoding As eEncoding
Dim saveImagesToDisk As Boolean
Dim imageFolder As String
Dim returnValue As String

returnValue = SautinSoftUtil.Rtf2Html(rtfText, 
	outputFormat, textEncoding, saveImagesToDisk, 
	imageFolder)
```

**C++**<br />
``` C++
public:
static String^ Rtf2Html(
	String^ rtfText, 
	eOutputFormat outputFormat = eOutputFormat::XHTML_10, 
	eEncoding textEncoding = eEncoding::UTF_8, 
	bool saveImagesToDisk = false, 
	String^ imageFolder = L"C:\"
)
```

**F#**<br />
``` F#
static member Rtf2Html : 
        rtfText : string * 
        ?outputFormat : eOutputFormat * 
        ?textEncoding : eEncoding * 
        ?saveImagesToDisk : bool * 
        ?imageFolder : string 
(* Defaults:
        let _outputFormat = defaultArg outputFormat eOutputFormat.XHTML_10
        let _textEncoding = defaultArg textEncoding eEncoding.UTF_8
        let _saveImagesToDisk = defaultArg saveImagesToDisk false
        let _imageFolder = defaultArg imageFolder "C:\"
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>rtfText</dt><dd>Type: System.String<br />The rich text to convert.</dd><dt>outputFormat (Optional)</dt><dd>Type: eOutputFormat<br />The output HTML format.</dd><dt>textEncoding (Optional)</dt><dd>Type: eEncoding<br />The text encoding.</dd><dt>saveImagesToDisk (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), converted images are saved to a directory on hard drive.</dd><dt>imageFolder (Optional)</dt><dd>Type: System.String<br />The image directory to save the images if *saveImagesToDisk* parameter is set to `true` (`True` in Visual Basic). 

 The directory must exist.</dd></dl>

#### Return Value
Type: String<br />The resulting text.

## Examples
This is a code example. 
**VB**<br />
``` VB
' RTF 2 HTML
Dim htmlString As String =
    Rtf2Html(File.ReadAllText("C:\File.rtf"),
             RtfToHtml.eOutputFormat.XHTML_10,
             RtfToHtml.eEncoding.UTF_8,
             True, "C:\")

File.WriteAllText("C:\File.html", htmlString)
Process.Start("C:\File.html")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SautinSoft_SautinSoftUtil">SautinSoftUtil Class</a><br /><a href="N_DevCase_ThirdParty_SautinSoft">DevCase.ThirdParty.SautinSoft Namespace</a><br />