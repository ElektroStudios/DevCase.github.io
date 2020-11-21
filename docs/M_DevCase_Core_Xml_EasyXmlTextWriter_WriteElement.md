# EasyXmlTextWriter.WriteElement Method 
 

Writes an Xml element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void WriteElement(
	string startElement,
	string element,
	Formatting indentation = Formatting.Indented
)
```

**VB**<br />
``` VB
Public Sub WriteElement ( 
	startElement As String,
	element As String,
	Optional indentation As Formatting = Formatting.Indented
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As EasyXmlTextWriter
Dim startElement As String
Dim element As String
Dim indentation As Formatting

instance.WriteElement(startElement, element, 
	indentation)
```

**C++**<br />
``` C++
public:
void WriteElement(
	String^ startElement, 
	String^ element, 
	Formatting indentation = Formatting::Indented
)
```

**F#**<br />
``` F#
member WriteElement : 
        startElement : string * 
        element : string * 
        ?indentation : Formatting 
(* Defaults:
        let _indentation = defaultArg indentation Formatting.Indented
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>startElement</dt><dd>Type: System.String<br />The starting element.</dd><dt>element</dt><dd>Type: System.String<br />The element.</dd><dt>indentation (Optional)</dt><dd>Type: System.Xml.Formatting<br />The Xml indentation formatting.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter Class</a><br /><a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />