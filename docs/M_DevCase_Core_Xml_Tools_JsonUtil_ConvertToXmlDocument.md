# JsonUtil.ConvertToXmlDocument Method 
 

Converts a JSON String to XmlDocument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XmlDocument ConvertToXmlDocument(
	string json,
	Encoding enc
)
```

**VB**<br />
``` VB
Public Shared Function ConvertToXmlDocument ( 
	json As String,
	enc As Encoding
) As XmlDocument
```

**VB Usage**<br />
``` VB Usage
Dim json As String
Dim enc As Encoding
Dim returnValue As XmlDocument

returnValue = JsonUtil.ConvertToXmlDocument(json, 
	enc)
```

**C++**<br />
``` C++
public:
static XmlDocument^ ConvertToXmlDocument(
	String^ json, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
static member ConvertToXmlDocument : 
        json : string * 
        enc : Encoding -> XmlDocument 

```


#### Parameters
&nbsp;<dl><dt>json</dt><dd>Type: System.String<br />The source JSON string.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The character encoding that must be used to read the JSON string.</dd></dl>

#### Return Value
Type: XmlDocument<br />The resulting XmlDocument.

## Examples
This is a code example. 
**VB**<br />
``` VB
        Dim json As String = <a>
{
    "colorsArray":[{
            "colorName":"red",
            "hexValue":"#f00"
        },
        {
            "colorName":"green",
            "hexValue":"#0f0"
        },
        {
            "colorName":"blue",
            "hexValue":"#00f"
        },
        {
            "colorName":"cyan",
            "hexValue":"#0ff"
        },
        {
            "colorName":"magenta",
            "hexValue":"#f0f"
        },
        {
            "colorName":"yellow",
            "hexValue":"#ff0"
        },
        {
            "colorName":"black",
            "hexValue":"#000"
        }
    ]
 }</a>.Value
 Dim xdoc As XmlDocument = ConvertToXmlDocument(json, Encoding.UTF8)

 Console.WriteLine(xml.InnerXml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Xml_Tools_JsonUtil">JsonUtil Class</a><br /><a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools Namespace</a><br />