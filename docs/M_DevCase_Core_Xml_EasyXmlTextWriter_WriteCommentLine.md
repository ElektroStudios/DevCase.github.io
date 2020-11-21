# EasyXmlTextWriter.WriteCommentLine Method 
 

Writes an Xml comment line.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void WriteCommentLine(
	string comment,
	Formatting indentation = Formatting.Indented
)
```

**VB**<br />
``` VB
Public Sub WriteCommentLine ( 
	comment As String,
	Optional indentation As Formatting = Formatting.Indented
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As EasyXmlTextWriter
Dim comment As String
Dim indentation As Formatting

instance.WriteCommentLine(comment, indentation)
```

**C++**<br />
``` C++
public:
void WriteCommentLine(
	String^ comment, 
	Formatting indentation = Formatting::Indented
)
```

**F#**<br />
``` F#
member WriteCommentLine : 
        comment : string * 
        ?indentation : Formatting 
(* Defaults:
        let _indentation = defaultArg indentation Formatting.Indented
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>comment</dt><dd>Type: System.String<br />The commentary to write.</dd><dt>indentation (Optional)</dt><dd>Type: System.Xml.Formatting<br />The Xml indentation formatting.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter Class</a><br /><a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />