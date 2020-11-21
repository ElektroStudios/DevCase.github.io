# UIAutomationUtil.FlashWindow Method (IWin32Window, FlashWindowFlags, UInt32, UInt32)
 

Flashes a Window and/or it's button in the TaskBar. 

 It does not change the active state of the window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool FlashWindow(
	IWin32Window window,
	FlashWindowFlags flashFlags,
	uint flashCount = 4294967295,
	uint flashDelay = 0
)
```

**VB**<br />
``` VB
Public Shared Function FlashWindow ( 
	window As IWin32Window,
	flashFlags As FlashWindowFlags,
	Optional flashCount As UInteger = 4294967295,
	Optional flashDelay As UInteger = 0
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim flashFlags As FlashWindowFlags
Dim flashCount As UInteger
Dim flashDelay As UInteger
Dim returnValue As Boolean

returnValue = UIAutomationUtil.FlashWindow(window, 
	flashFlags, flashCount, flashDelay)
```

**C++**<br />
``` C++
public:
static bool FlashWindow(
	IWin32Window^ window, 
	FlashWindowFlags flashFlags, 
	unsigned int flashCount = 4294967295, 
	unsigned int flashDelay = 0
)
```

**F#**<br />
``` F#
static member FlashWindow : 
        window : IWin32Window * 
        flashFlags : FlashWindowFlags * 
        ?flashCount : uint32 * 
        ?flashDelay : uint32 
(* Defaults:
        let _flashCount = defaultArg flashCount 4294967295
        let _flashDelay = defaultArg flashDelay 0
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window to flash.</dd><dt>flashFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FlashWindowFlags">DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags</a><br />The flash flags.</dd><dt>flashCount (Optional)</dt><dd>Type: System.UInt32<br />The number of times to flash the window.</dd><dt>flashDelay (Optional)</dt><dd>Type: System.UInt32<br />The rate at which the window is to be flashed, in milliseconds. 

 If *flashDelay* is zero, the function uses the default cursor blink rate.</dd></dl>

#### Return Value
Type: Boolean<br />The return value specifies the window's state before the call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FlashWindowEx">FlashWindowEx(FlashWindowInfo)</a> function. 

 If the window caption was drawn as active before the call, the return value is nonzero. Otherwise, the return value is zero.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Flash the Button TaskBar until the window becomes active.
FlashWindow(Me, FlashWindowFlags.TaskBar Or FlashWindowFlags.UntilForeground)

' Flash the Caption and the Button TaskBar until the "Stop" flag is set.
FlashWindow(Me, FlashWindowFlags.All Or FlashWindowFlags.UntilStop)

' Set the "Stop" flag to stop flashing.
FlashWindow(Me, FlashWindowFlags.Stop)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_FlashWindow">FlashWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />