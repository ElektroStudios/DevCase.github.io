# ColorString.CSharp Property 
 

Gets the C# color representation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	CSharpColorFormat format
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CSharp ( 
	format As CSharpColorFormat
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ColorString
Dim format As CSharpColorFormat
Dim value As String

value = instance.CSharp(format)

```

**C++**<br />
``` C++
public:
property String^ CSharp[CSharpColorFormat format] {
	String^ get (CSharpColorFormat format);
}
```

**F#**<br />
``` F#
member CSharp : string with get

```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Imaging_CSharpColorFormat">DevCase.Core.Imaging.CSharpColorFormat</a><br />The color format.</dd></dl>

#### Property Value
Type: String<br />The C# color representation.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ColorString">ColorString Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />