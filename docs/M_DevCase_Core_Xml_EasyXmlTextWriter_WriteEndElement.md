# EasyXmlTextWriter.WriteEndElement Method 
 

Writes the end of an Xml element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void WriteEndElement(
	Formatting indentation = Formatting.Indented
)
```

**VB**<br />
``` VB
Public Sub WriteEndElement ( 
	Optional indentation As Formatting = Formatting.Indented
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As EasyXmlTextWriter
Dim indentation As Formatting

instance.WriteEndElement(indentation)
```

**C++**<br />
``` C++
public:
void WriteEndElement(
	Formatting indentation = Formatting::Indented
)
```

**F#**<br />
``` F#
member WriteEndElement : 
        ?indentation : Formatting 
(* Defaults:
        let _indentation = defaultArg indentation Formatting.Indented
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>indentation (Optional)</dt><dd>Type: System.Xml.Formatting<br />The Xml indentation formatting.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter Class</a><br /><a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />