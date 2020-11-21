# ColorString.Inequality Operator 
 

Implements the operator <>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator !=(
	ColorString colorString1,
	ColorString colorString2
)
```

**VB**<br />
``` VB
Public Shared Operator <> ( 
	colorString1 As ColorString,
	colorString2 As ColorString
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim colorString1 As ColorString
Dim colorString2 As ColorString
Dim returnValue As Boolean

returnValue = (colorString1 <> colorString2)
```

**C++**<br />
``` C++
public:
static bool operator !=(
	ColorString^ colorString1, 
	ColorString^ colorString2
)
```

**F#**<br />
``` F#
static let inline (<>)
        colorString1 : ColorString * 
        colorString2 : ColorString  : bool
```


#### Parameters
&nbsp;<dl><dt>colorString1</dt><dd>Type: <a href="T_DevCase_Core_Imaging_ColorString">DevCase.Core.Imaging.ColorString</a><br />The first <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a> to evaluate.</dd><dt>colorString2</dt><dd>Type: <a href="T_DevCase_Core_Imaging_ColorString">DevCase.Core.Imaging.ColorString</a><br />The second <a href="T_DevCase_Core_Imaging_ColorString">ColorString</a> to evaluate.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ColorString">ColorString Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />