# GraphicsQualityContainer Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public GraphicsQualityContainer(
	CompositingQuality compositingQuality = CompositingQuality.Default,
	InterpolationMode interpolationMode = InterpolationMode.Default,
	PixelOffsetMode pixelOffsetMode = PixelOffsetMode.Default,
	QualityMode qualityMode = QualityMode.Default,
	SmoothingMode smoothingMode = SmoothingMode.Default,
	TextRenderingHint textRenderingHint = TextRenderingHint.SystemDefault
)
```

**VB**<br />
``` VB
Public Sub New ( 
	Optional compositingQuality As CompositingQuality = CompositingQuality.Default,
	Optional interpolationMode As InterpolationMode = InterpolationMode.Default,
	Optional pixelOffsetMode As PixelOffsetMode = PixelOffsetMode.Default,
	Optional qualityMode As QualityMode = QualityMode.Default,
	Optional smoothingMode As SmoothingMode = SmoothingMode.Default,
	Optional textRenderingHint As TextRenderingHint = TextRenderingHint.SystemDefault
)
```

**VB Usage**<br />
``` VB Usage
Dim compositingQuality As CompositingQuality
Dim interpolationMode As InterpolationMode
Dim pixelOffsetMode As PixelOffsetMode
Dim qualityMode As QualityMode
Dim smoothingMode As SmoothingMode
Dim textRenderingHint As TextRenderingHint

Dim instance As New GraphicsQualityContainer(compositingQuality, 
	interpolationMode, pixelOffsetMode, 
	qualityMode, smoothingMode, textRenderingHint)
```

**C++**<br />
``` C++
public:
GraphicsQualityContainer(
	CompositingQuality compositingQuality = CompositingQuality::Default, 
	InterpolationMode interpolationMode = InterpolationMode::Default, 
	PixelOffsetMode pixelOffsetMode = PixelOffsetMode::Default, 
	QualityMode qualityMode = QualityMode::Default, 
	SmoothingMode smoothingMode = SmoothingMode::Default, 
	TextRenderingHint textRenderingHint = TextRenderingHint::SystemDefault
)
```

**F#**<br />
``` F#
new : 
        ?compositingQuality : CompositingQuality * 
        ?interpolationMode : InterpolationMode * 
        ?pixelOffsetMode : PixelOffsetMode * 
        ?qualityMode : QualityMode * 
        ?smoothingMode : SmoothingMode * 
        ?textRenderingHint : TextRenderingHint 
(* Defaults:
        let _compositingQuality = defaultArg compositingQuality CompositingQuality.Default
        let _interpolationMode = defaultArg interpolationMode InterpolationMode.Default
        let _pixelOffsetMode = defaultArg pixelOffsetMode PixelOffsetMode.Default
        let _qualityMode = defaultArg qualityMode QualityMode.Default
        let _smoothingMode = defaultArg smoothingMode SmoothingMode.Default
        let _textRenderingHint = defaultArg textRenderingHint TextRenderingHint.SystemDefault
*)
-> GraphicsQualityContainer
```


#### Parameters
&nbsp;<dl><dt>compositingQuality (Optional)</dt><dd>Type: System.Drawing.Drawing2D.CompositingQuality<br />The quality level to use during compositing.</dd><dt>interpolationMode (Optional)</dt><dd>Type: System.Drawing.Drawing2D.InterpolationMode<br />The algorithm that is used when images are scaled or rotated.</dd><dt>pixelOffsetMode (Optional)</dt><dd>Type: System.Drawing.Drawing2D.PixelOffsetMode<br />A value that indicates how pixels are offset during rendering.</dd><dt>qualityMode (Optional)</dt><dd>Type: System.Drawing.Drawing2D.QualityMode<br />The overall quality when rendering GDI+ objects.</dd><dt>smoothingMode (Optional)</dt><dd>Type: System.Drawing.Drawing2D.SmoothingMode<br />A value that indicates whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas.</dd><dt>textRenderingHint (Optional)</dt><dd>Type: System.Drawing.Text.TextRenderingHint<br />The quality of text rendering.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_GraphicsQualityContainer">GraphicsQualityContainer Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />