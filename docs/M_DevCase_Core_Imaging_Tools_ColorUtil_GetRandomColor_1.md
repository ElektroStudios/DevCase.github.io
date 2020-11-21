# ColorUtil.GetRandomColor Method (Byte, Byte, Byte, Byte, Byte, Byte, Byte, Byte)
 

Generates a random A-RGB color between the specified range of values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color GetRandomColor(
	byte alphaMin,
	byte alphaMax,
	byte redMin,
	byte redMax,
	byte greenMin,
	byte greenMax,
	byte blueMin,
	byte blueMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomColor ( 
	alphaMin As Byte,
	alphaMax As Byte,
	redMin As Byte,
	redMax As Byte,
	greenMin As Byte,
	greenMax As Byte,
	blueMin As Byte,
	blueMax As Byte
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim alphaMin As Byte
Dim alphaMax As Byte
Dim redMin As Byte
Dim redMax As Byte
Dim greenMin As Byte
Dim greenMax As Byte
Dim blueMin As Byte
Dim blueMax As Byte
Dim returnValue As Color

returnValue = ColorUtil.GetRandomColor(alphaMin, 
	alphaMax, redMin, redMax, greenMin, 
	greenMax, blueMin, blueMax)
```

**C++**<br />
``` C++
public:
static Color GetRandomColor(
	unsigned char alphaMin, 
	unsigned char alphaMax, 
	unsigned char redMin, 
	unsigned char redMax, 
	unsigned char greenMin, 
	unsigned char greenMax, 
	unsigned char blueMin, 
	unsigned char blueMax
)
```

**F#**<br />
``` F#
static member GetRandomColor : 
        alphaMin : byte * 
        alphaMax : byte * 
        redMin : byte * 
        redMax : byte * 
        greenMin : byte * 
        greenMax : byte * 
        blueMin : byte * 
        blueMax : byte -> Color 

```


#### Parameters
&nbsp;<dl><dt>alphaMin</dt><dd>Type: System.Byte<br />The Alpha channel minimum value.</dd><dt>alphaMax</dt><dd>Type: System.Byte<br />The Alpha channel maximum value.</dd><dt>redMin</dt><dd>Type: System.Byte<br />The Red channel minimum value.</dd><dt>redMax</dt><dd>Type: System.Byte<br />The Red channel maximum value.</dd><dt>greenMin</dt><dd>Type: System.Byte<br />The Green channel minimum value.</dd><dt>greenMax</dt><dd>Type: System.Byte<br />The Green channel maximum value.</dd><dt>blueMin</dt><dd>Type: System.Byte<br />The Blue channel minimum value.</dd><dt>blueMax</dt><dd>Type: System.Byte<br />The Blue channel maximum value.</dd></dl>

#### Return Value
Type: Color<br />The random Color.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomColor">GetRandomColor Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />