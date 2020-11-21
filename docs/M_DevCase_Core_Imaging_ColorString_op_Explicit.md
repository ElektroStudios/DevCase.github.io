# ColorString&nbsp;Explicit Conversion (Color to ColorString)
 

Performs an implicit conversion from Color to <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static explicit operator ColorString (
	Color color
)
```

**VB**<br />
``` VB
Public Shared Narrowing Operator CType ( 
	color As Color
) As ColorString
```

**VB Usage**<br />
``` VB Usage
Dim input As Color
Dim output As ColorString

output = CType(input, ColorString)
```

**C++**<br />
``` C++
static explicit operator ColorString^ (
	Color color
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Drawing.Color<br />The Color.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a><br />The resulting <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a> of the conversion.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ColorString">ColorString Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />