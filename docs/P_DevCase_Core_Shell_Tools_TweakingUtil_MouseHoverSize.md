# TweakingUtil.MouseHoverSize Property 
 

Gets or sets the width and height, in pixels, of the rectangle which the mouse pointer has to stay for TrackMouseEvent to generate a WM_MOUSEHOVER message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Size MouseHoverSize { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MouseHoverSize As Size
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Size

value = TweakingUtil.MouseHoverSize

TweakingUtil.MouseHoverSize = value
```

**C++**<br />
``` C++
public:
static property Size MouseHoverSize {
	Size get ();
	void set (Size value);
}
```

**F#**<br />
``` F#
static member MouseHoverSize : Size with get, set

```


#### Property Value
Type: Size<br />The width and height, in pixels, of the rectangle which the mouse pointer has to stay for TrackMouseEvent to generate a WM_MOUSEHOVER message.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Width should be greater than 0.;value</td></tr><tr><td>ArgumentException</td><td>Height should be greater than 0.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />