# DrawingUtil.GetRandomRectangleF Method (SizeF)
 

Gets a random RectangleF with a size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RectangleF GetRandomRectangleF(
	SizeF sizeMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangleF ( 
	sizeMax As SizeF
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim sizeMax As SizeF
Dim returnValue As RectangleF

returnValue = DrawingUtil.GetRandomRectangleF(sizeMax)
```

**C++**<br />
``` C++
public:
static RectangleF GetRandomRectangleF(
	SizeF sizeMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangleF : 
        sizeMax : SizeF -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>sizeMax</dt><dd>Type: System.Drawing.SizeF<br />A SizeF that specifies the maximum width and height.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangleF">GetRandomRectangleF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />