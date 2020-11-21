# ColorString.VisualStudio Property 
 

Gets the VisualStudio color representation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	VisualStudioColorFormat format
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property VisualStudio ( 
	format As VisualStudioColorFormat
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ColorString
Dim format As VisualStudioColorFormat
Dim value As String

value = instance.VisualStudio(format)

```

**C++**<br />
``` C++
public:
property String^ VisualStudio[VisualStudioColorFormat format] {
	String^ get (VisualStudioColorFormat format);
}
```

**F#**<br />
``` F#
member VisualStudio : string with get

```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Imaging_VisualStudioColorFormat">DevCase.Core.Imaging.VisualStudioColorFormat</a><br />The color format.</dd></dl>

#### Property Value
Type: String<br />The VisualStudio color representation.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ColorString">ColorString Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />