# SautinSoftUtil.Html2Txt Method 
 

Converts HTML text to TXT (Plain Text).

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SautinSoft">DevCase.ThirdParty.SautinSoft</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Html2Txt(
	string htmlText,
	eEncoding textEncoding = eEncoding.AutoDetect,
	bool preservePageBreaks = false,
	PageSize pageSize = PageSize.Auto,
	ePageNumbers pagenumbers = ePageNumbers.PageNumFirst,
	string pagenumbersFormat = "Page {page} of {numpages}",
	eAlign pageAlignment = eAlign.Undefined,
	PageOrientation pageOrientation = PageOrientation.Auto,
	string pageHeader = null,
	string pageFooter = null,
	eImageCompatible imageCompatibility = eImageCompatible.WordPad
)
```

**VB**<br />
``` VB
Public Shared Function Html2Txt ( 
	htmlText As String,
	Optional textEncoding As eEncoding = eEncoding.AutoDetect,
	Optional preservePageBreaks As Boolean = false,
	Optional pageSize As PageSize = PageSize.Auto,
	Optional pagenumbers As ePageNumbers = ePageNumbers.PageNumFirst,
	Optional pagenumbersFormat As String = "Page {page} of {numpages}",
	Optional pageAlignment As eAlign = eAlign.Undefined,
	Optional pageOrientation As PageOrientation = PageOrientation.Auto,
	Optional pageHeader As String = Nothing,
	Optional pageFooter As String = Nothing,
	Optional imageCompatibility As eImageCompatible = eImageCompatible.WordPad
) As String
```

**VB Usage**<br />
``` VB Usage
Dim htmlText As String
Dim textEncoding As eEncoding
Dim preservePageBreaks As Boolean
Dim pageSize As PageSize
Dim pagenumbers As ePageNumbers
Dim pagenumbersFormat As String
Dim pageAlignment As eAlign
Dim pageOrientation As PageOrientation
Dim pageHeader As String
Dim pageFooter As String
Dim imageCompatibility As eImageCompatible
Dim returnValue As String

returnValue = SautinSoftUtil.Html2Txt(htmlText, 
	textEncoding, preservePageBreaks, 
	pageSize, pagenumbers, pagenumbersFormat, 
	pageAlignment, pageOrientation, 
	pageHeader, pageFooter, imageCompatibility)
```

**C++**<br />
``` C++
public:
static String^ Html2Txt(
	String^ htmlText, 
	eEncoding textEncoding = eEncoding::AutoDetect, 
	bool preservePageBreaks = false, 
	PageSize pageSize = PageSize::Auto, 
	ePageNumbers pagenumbers = ePageNumbers::PageNumFirst, 
	String^ pagenumbersFormat = L"Page {page} of {numpages}", 
	eAlign pageAlignment = eAlign::Undefined, 
	PageOrientation pageOrientation = PageOrientation::Auto, 
	String^ pageHeader = nullptr, 
	String^ pageFooter = nullptr, 
	eImageCompatible imageCompatibility = eImageCompatible::WordPad
)
```

**F#**<br />
``` F#
static member Html2Txt : 
        htmlText : string * 
        ?textEncoding : eEncoding * 
        ?preservePageBreaks : bool * 
        ?pageSize : PageSize * 
        ?pagenumbers : ePageNumbers * 
        ?pagenumbersFormat : string * 
        ?pageAlignment : eAlign * 
        ?pageOrientation : PageOrientation * 
        ?pageHeader : string * 
        ?pageFooter : string * 
        ?imageCompatibility : eImageCompatible 
(* Defaults:
        let _textEncoding = defaultArg textEncoding eEncoding.AutoDetect
        let _preservePageBreaks = defaultArg preservePageBreaks false
        let _pageSize = defaultArg pageSize PageSize.Auto
        let _pagenumbers = defaultArg pagenumbers ePageNumbers.PageNumFirst
        let _pagenumbersFormat = defaultArg pagenumbersFormat "Page {page} of {numpages}"
        let _pageAlignment = defaultArg pageAlignment eAlign.Undefined
        let _pageOrientation = defaultArg pageOrientation PageOrientation.Auto
        let _pageHeader = defaultArg pageHeader null
        let _pageFooter = defaultArg pageFooter null
        let _imageCompatibility = defaultArg imageCompatibility eImageCompatible.WordPad
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>htmlText</dt><dd>Type: System.String<br />The HTML text to convert.</dd><dt>textEncoding (Optional)</dt><dd>Type: eEncoding<br />The text encoding.</dd><dt>preservePageBreaks (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic) page breaks are preserved on the conversion.</dd><dt>pageSize (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_SautinSoft_PageSize">DevCase.ThirdParty.SautinSoft.PageSize</a><br />The page size.</dd><dt>pagenumbers (Optional)</dt><dd>Type: ePageNumbers<br />The page numbers.</dd><dt>pagenumbersFormat (Optional)</dt><dd>Type: System.String<br />The page numbers format.</dd><dt>pageAlignment (Optional)</dt><dd>Type: eAlign<br />The page alignment.</dd><dt>pageOrientation (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_SautinSoft_PageOrientation">DevCase.ThirdParty.SautinSoft.PageOrientation</a><br />The page orientation.</dd><dt>pageHeader (Optional)</dt><dd>Type: System.String<br />The page header text.</dd><dt>pageFooter (Optional)</dt><dd>Type: System.String<br />The page footer text.</dd><dt>imageCompatibility (Optional)</dt><dd>Type: eImageCompatible<br />The image compatibility if the document contains images. 

 RichTexBox control and WordPad can't show jpeg and png images inside RTF, they can show only bitmap images. Microsoft Word can show images in jpeg, png, etc. 

 If this property is set to WordPad images will be stored as BMP inside RTF.</dd></dl>

#### Return Value
Type: String<br />The resulting text.

## Examples
This is a code example. 
**VB**<br />
``` VB
' HTML 2 TXT
RichTextBox1.Text =
    Html2Txt(File.ReadAllText("C:\File.htm", Encoding.Default),
    HtmlToRtf.eEncoding.AutoDetect, False,
    PageSize.Auto, HtmlToRtf.ePageNumbers.PageNumFirst,
    "Page {page} of {numpages}", HtmlToRtf.eAlign.Undefined,
    PageOrientation.Auto, "Header", "Footer",
    HtmlToRtf.eImageCompatible.WordPad)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SautinSoft_SautinSoftUtil">SautinSoftUtil Class</a><br /><a href="N_DevCase_ThirdParty_SautinSoft">DevCase.ThirdParty.SautinSoft Namespace</a><br />