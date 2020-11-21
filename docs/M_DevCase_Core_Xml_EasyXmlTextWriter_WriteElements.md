# EasyXmlTextWriter.WriteElements Method 
 

Writes multiple Xml elements.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void WriteElements(
	string[,] elements,
	Formatting indentation = Formatting.Indented
)
```

**VB**<br />
``` VB
Public Sub WriteElements ( 
	elements As String(,),
	Optional indentation As Formatting = Formatting.Indented
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As EasyXmlTextWriter
Dim elements As String(,)
Dim indentation As Formatting

instance.WriteElements(elements, indentation)
```

**C++**<br />
``` C++
public:
void WriteElements(
	array<String^,2>^ elements, 
	Formatting indentation = Formatting::Indented
)
```

**F#**<br />
``` F#
member WriteElements : 
        elements : string[,] * 
        ?indentation : Formatting 
(* Defaults:
        let _indentation = defaultArg indentation Formatting.Indented
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>elements</dt><dd>Type: System.String[,]<br />The elements.</dd><dt>indentation (Optional)</dt><dd>Type: System.Xml.Formatting<br />The Xml indentation formatting.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter Class</a><br /><a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />