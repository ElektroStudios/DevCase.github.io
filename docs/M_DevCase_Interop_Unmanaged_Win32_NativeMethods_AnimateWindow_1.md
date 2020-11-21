# NativeMethods.AnimateWindow Method (SafeHandle, Int32, WindowAnimation)
 

Produces special effects when showing or hiding a window. 

 This doesn't show the window so make sure you call Show() or set Visible property to `true` (`True` in Visual Basic) after calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AnimateWindow">AnimateWindow(IntPtr, Int32, WindowAnimation)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool AnimateWindow(
	SafeHandle hWnd,
	int time,
	WindowAnimation animation
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function AnimateWindow ( 
	hWnd As SafeHandle,
	time As Integer,
	animation As WindowAnimation
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim time As Integer
Dim animation As WindowAnimation
Dim returnValue As Boolean

returnValue = NativeMethods.AnimateWindow(hWnd, 
	time, animation)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool AnimateWindow(
	SafeHandle^ hWnd, 
	int time, 
	WindowAnimation animation
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member AnimateWindow : 
        hWnd : SafeHandle * 
        time : int * 
        animation : WindowAnimation -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the window to animate. 

 The calling thread must own this window.</dd><dt>time</dt><dd>Type: System.Int32<br />The time it takes to play the animation, in milliseconds. 

 Typically, an animation takes 200 milliseconds to play.</dd><dt>animation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowAnimation">DevCase.Interop.Unmanaged.Win32.Enums.WindowAnimation</a><br />The type of animation.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 The function will fail in the following situations: 

 If the window is already visible and you are trying to show the window. 

 If the window is already hidden and you are trying to hide the window. 

 When trying to animate a child window with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowAnimation">ShowFade</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowAnimation">HideFade</a>. 

 If the thread does not own the window. Note that, in this case, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AnimateWindow">AnimateWindow(IntPtr, Int32, WindowAnimation)</a> fails but GetLastWin32Error() returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632669%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632669%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_AnimateWindow">AnimateWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />