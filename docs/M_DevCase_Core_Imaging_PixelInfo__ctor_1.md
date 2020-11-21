# PixelInfo Constructor (Pen, Int32, Point)
 

Initializes a new instance of the <a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PixelInfo(
	Pen pen,
	int position,
	Point location
)
```

**VB**<br />
``` VB
Public Sub New ( 
	pen As Pen,
	position As Integer,
	location As Point
)
```

**VB Usage**<br />
``` VB Usage
Dim pen As Pen
Dim position As Integer
Dim location As Point

Dim instance As New PixelInfo(pen, position, 
	location)
```

**C++**<br />
``` C++
public:
PixelInfo(
	Pen^ pen, 
	int position, 
	Point location
)
```

**F#**<br />
``` F#
new : 
        pen : Pen * 
        position : int * 
        location : Point -> PixelInfo
```


#### Parameters
&nbsp;<dl><dt>pen</dt><dd>Type: System.Drawing.Pen<br />The Pen that contains the <a href="P_DevCase_Core_Imaging_PixelInfo_Color">Color</a> of the pixel.</dd><dt>position</dt><dd>Type: System.Int32<br />The index position of the pixel in the image.</dd><dt>location</dt><dd>Type: System.Drawing.Point<br />The location coordinates of the pixel relative to the image.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo Class</a><br /><a href="Overload_DevCase_Core_Imaging_PixelInfo__ctor">PixelInfo Overload</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />