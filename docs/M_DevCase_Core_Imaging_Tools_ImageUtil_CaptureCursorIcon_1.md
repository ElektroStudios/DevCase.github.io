# ImageUtil.CaptureCursorIcon Method (Point)
 

Captures the mouse cursor icon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap CaptureCursorIcon(
	ref Point refPoint
)
```

**VB**<br />
``` VB
Public Shared Function CaptureCursorIcon ( 
	ByRef refPoint As Point
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim refPoint As Point
Dim returnValue As Bitmap

returnValue = ImageUtil.CaptureCursorIcon(refPoint)
```

**C++**<br />
``` C++
public:
static Bitmap^ CaptureCursorIcon(
	Point% refPoint
)
```

**F#**<br />
``` F#
static member CaptureCursorIcon : 
        refPoint : Point byref -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>refPoint</dt><dd>Type: System.Drawing.Point<br />A Point structure that receives the mouse position, in screen coordinates.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_CaptureCursorIcon">CaptureCursorIcon Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />