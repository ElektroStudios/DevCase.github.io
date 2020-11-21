# XmlUtil.XmlBeautifier Method (String, String, Boolean, Encoding)
 

Beautifies the contents of an Xml document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string XmlBeautifier(
	string xmlText,
	string indentChars = "",
	bool indentOnAttributes = false,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function XmlBeautifier ( 
	xmlText As String,
	Optional indentChars As String = "",
	Optional indentOnAttributes As Boolean = false,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim xmlText As String
Dim indentChars As String
Dim indentOnAttributes As Boolean
Dim enc As Encoding
Dim returnValue As String

returnValue = XmlUtil.XmlBeautifier(xmlText, 
	indentChars, indentOnAttributes, 
	enc)
```

**C++**<br />
``` C++
public:
static String^ XmlBeautifier(
	String^ xmlText, 
	String^ indentChars = L"", 
	bool indentOnAttributes = false, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member XmlBeautifier : 
        xmlText : string * 
        ?indentChars : string * 
        ?indentOnAttributes : bool * 
        ?enc : Encoding 
(* Defaults:
        let _indentChars = defaultArg indentChars ""
        let _indentOnAttributes = defaultArg indentOnAttributes false
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>xmlText</dt><dd>Type: System.String<br />The Xml text content. It can be an entire document or a fragment.</dd><dt>indentChars (Optional)</dt><dd>Type: System.String<br />The string that is used to indent the Xml. 

 Default value is Tab</dd><dt>indentOnAttributes (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), attributes will be separated by newlines.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The Xml text encoding to use. 

 Default value is Default.</dd></dl>

#### Return Value
Type: String<br />The beautified Xml text.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>xmlText</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim enc As Encoding = Encoding.Default

Dim unformattedXmlDocument As String =
    File.ReadAllText("C:\Unformatted Document.xml", enc)

Dim formattedXmlDocument As String =
    XmlBeautifier(xmlText:=unformattedXmlDocument,
                  indentChars:=New String(" "c, 2),
                  indentOnAttributes:=True,
                  enc:=enc)

File.WriteAllText("C:\Formatted Document.xml", formattedXmlDocument, enc)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Xml_Tools_XmlUtil">XmlUtil Class</a><br /><a href="Overload_DevCase_Core_Xml_Tools_XmlUtil_XmlBeautifier">XmlBeautifier Overload</a><br /><a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools Namespace</a><br />