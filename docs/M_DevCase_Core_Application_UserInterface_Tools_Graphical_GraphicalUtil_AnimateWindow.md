# GraphicalUtil.AnimateWindow Method 
 

Produces special effects when showing or hiding a window. 

 This doesn't show the window so make sure you call Show() or set Visible property to `true` (`True` in Visual Basic) after calling AnimateWindow(IWin32Window, Int32, WindowAnimation).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AnimateWindow(
	IWin32Window window,
	int time,
	WindowAnimation animation
)
```

**VB**<br />
``` VB
Public Shared Function AnimateWindow ( 
	window As IWin32Window,
	time As Integer,
	animation As WindowAnimation
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim time As Integer
Dim animation As WindowAnimation
Dim returnValue As Boolean

returnValue = GraphicalUtil.AnimateWindow(window, 
	time, animation)
```

**C++**<br />
``` C++
public:
static bool AnimateWindow(
	IWin32Window^ window, 
	int time, 
	WindowAnimation animation
)
```

**F#**<br />
``` F#
static member AnimateWindow : 
        window : IWin32Window * 
        time : int * 
        animation : WindowAnimation -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window to animate. 

 The calling thread must own this window.</dd><dt>time</dt><dd>Type: System.Int32<br />The time it takes to play the animation, in milliseconds. 

 Typically, an animation takes 200 milliseconds to play.</dd><dt>animation</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_WindowAnimation">DevCase.Core.Application.UserInterface.WindowAnimation</a><br />The type of animation.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 The function will fail in the following situations: 

 If the window is already visible and you are trying to show the window. 

 If the window is already hidden and you are trying to hide the window. 

 When trying to animate a child window with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowAnimation">ShowFade</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowAnimation">HideFade</a>. 

 If the thread does not own the window.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />