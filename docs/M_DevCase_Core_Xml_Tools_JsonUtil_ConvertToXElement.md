# JsonUtil.ConvertToXElement Method 
 

Converts a JSON String to XElement.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XElement ConvertToXElement(
	string json,
	Encoding enc
)
```

**VB**<br />
``` VB
Public Shared Function ConvertToXElement ( 
	json As String,
	enc As Encoding
) As XElement
```

**VB Usage**<br />
``` VB Usage
Dim json As String
Dim enc As Encoding
Dim returnValue As XElement

returnValue = JsonUtil.ConvertToXElement(json, 
	enc)
```

**C++**<br />
``` C++
public:
static XElement^ ConvertToXElement(
	String^ json, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
static member ConvertToXElement : 
        json : string * 
        enc : Encoding -> XElement 

```


#### Parameters
&nbsp;<dl><dt>json</dt><dd>Type: System.String<br />The source JSON string.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The character encoding that must be used to read the JSON string.</dd></dl>

#### Return Value
Type: XElement<br />The resulting XElement.

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
 Dim xml As XElement = ConvertToXElement(json, Encoding.UTF8)

 Dim firstColorName As String = xml.<colorsArray>.<item>(0).<colorName>.Value
 Dim firsHexValue As String = xml.<colorsArray>.<item>(0).<hexValue>.Value

 Console.WriteLine(String.Format("Color Name: {0}; Hex. Value: {1}", firstColorName, firsHexValue))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Xml_Tools_JsonUtil">JsonUtil Class</a><br /><a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools Namespace</a><br />