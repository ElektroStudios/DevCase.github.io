# ColorString&nbsp;Implicit Conversion (ColorString to Color)
 

Performs an implicit conversion from <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a> to Color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator Color (
	ColorString colorString
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	colorString As ColorString
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim input As ColorString
Dim output As Color

output = CType(input, Color)
```

**C++**<br />
``` C++
static implicit operator Color (
	ColorString^ colorString
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>colorString</dt><dd>Type: <a href="T_DevCase_Core_Imaging_ColorString">DevCase.Core.Imaging.ColorString</a><br />The <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a>.</dd></dl>

#### Return Value
Type: Color<br />The resulting Color of the conversion.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ColorString">ColorString Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />