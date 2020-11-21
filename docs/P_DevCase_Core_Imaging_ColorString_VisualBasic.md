# ColorString.VisualBasic Property 
 

Gets the VisualBasic color representation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	VisualBasicColorFormat format
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property VisualBasic ( 
	format As VisualBasicColorFormat
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ColorString
Dim format As VisualBasicColorFormat
Dim value As String

value = instance.VisualBasic(format)

```

**C++**<br />
``` C++
public:
property String^ VisualBasic[VisualBasicColorFormat format] {
	String^ get (VisualBasicColorFormat format);
}
```

**F#**<br />
``` F#
member VisualBasic : string with get

```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Imaging_VisualBasicColorFormat">DevCase.Core.Imaging.VisualBasicColorFormat</a><br />The color format.</dd></dl>

#### Property Value
Type: String<br />The VisualBasic color representation.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ColorString">ColorString Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />