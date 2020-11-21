# ImageUtil.TakeScreenshotFromWpfElement Method 
 

Takes a screenshot of a WPF UIElement.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image TakeScreenshotFromWpfElement(
	UIElement element,
	bool includeMouse
)
```

**VB**<br />
``` VB
Public Shared Function TakeScreenshotFromWpfElement ( 
	element As UIElement,
	includeMouse As Boolean
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim element As UIElement
Dim includeMouse As Boolean
Dim returnValue As Image

returnValue = ImageUtil.TakeScreenshotFromWpfElement(element, 
	includeMouse)
```

**C++**<br />
``` C++
public:
static Image^ TakeScreenshotFromWpfElement(
	UIElement^ element, 
	bool includeMouse
)
```

**F#**<br />
``` F#
static member TakeScreenshotFromWpfElement : 
        element : UIElement * 
        includeMouse : bool -> Image 

```


#### Parameters
&nbsp;<dl><dt>element</dt><dd>Type: System.Windows.UIElement<br />The WPF element to take the snapshot from.</dd><dt>includeMouse</dt><dd>Type: System.Boolean<br />\[Missing <param name="includeMouse"/> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.TakeScreenshotFromWpfElement(System.Windows.UIElement,System.Boolean)"\]</dd></dl>

#### Return Value
Type: Image<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />