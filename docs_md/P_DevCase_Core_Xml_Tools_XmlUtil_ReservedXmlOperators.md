# XmlUtil.ReservedXmlOperators Property 
 

Gets the reserved Xml operators.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static char[] ReservedXmlOperators { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ReservedXmlOperators As Char()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Char()

value = XmlUtil.ReservedXmlOperators

```

**C++**<br />
``` C++
public:
static property array<wchar_t>^ ReservedXmlOperators {
	array<wchar_t>^ get ();
}
```

**F#**<br />
``` F#
static member ReservedXmlOperators : char[] with get

```


#### Property Value
Type: Char[]<br />The reserved Xml operators.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim reservedChars As String = New String(ReservedXmlOperators)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Xml_Tools_XmlUtil">XmlUtil Class</a><br /><a href="N_DevCase_Core_Xml_Tools">DevCase.Core.Xml.Tools Namespace</a><br />