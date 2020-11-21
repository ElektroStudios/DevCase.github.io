# EasyXmlTextWriter.WriteEof Method 
 

Writes the ending Xml end of file. This method should be called to terminate writting the Xml.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void WriteEof(
	bool closeXmlWriter = false
)
```

**VB**<br />
``` VB
Public Sub WriteEof ( 
	Optional closeXmlWriter As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As EasyXmlTextWriter
Dim closeXmlWriter As Boolean

instance.WriteEof(closeXmlWriter)
```

**C++**<br />
``` C++
public:
void WriteEof(
	bool closeXmlWriter = false
)
```

**F#**<br />
``` F#
member WriteEof : 
        ?closeXmlWriter : bool 
(* Defaults:
        let _closeXmlWriter = defaultArg closeXmlWriter false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>closeXmlWriter (Optional)</dt><dd>Type: System.Boolean<br />if set to `true` (`True` in Visual Basic), closes the XmlTextWriter instance.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter Class</a><br /><a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />