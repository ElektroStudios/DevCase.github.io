# UIAutomationUtil.CaretCreate Method (IWin32Window, Bitmap, Int32, Int32)
 

Create a new caret from an image for the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CaretCreate(
	IWin32Window window,
	Bitmap bmp,
	int width,
	int height
)
```

**VB**<br />
``` VB
Public Shared Sub CaretCreate ( 
	window As IWin32Window,
	bmp As Bitmap,
	width As Integer,
	height As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim bmp As Bitmap
Dim width As Integer
Dim height As Integer

UIAutomationUtil.CaretCreate(window, bmp, width, 
	height)
```

**C++**<br />
``` C++
public:
static void CaretCreate(
	IWin32Window^ window, 
	Bitmap^ bmp, 
	int width, 
	int height
)
```

**F#**<br />
``` F#
static member CaretCreate : 
        window : IWin32Window * 
        bmp : Bitmap * 
        width : int * 
        height : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The image to use as caret.</dd><dt>width</dt><dd>Type: System.Int32<br />The width of the caret cursor.</dd><dt>height</dt><dd>Type: System.Int32<br />The width of the caret cursor.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_CaretCreate">CaretCreate Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />