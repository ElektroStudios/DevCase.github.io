# NativeMethods.SendNotifyMessage Method (IntPtr, UInt32, IntPtr, IntPtr)
 

Sends the specified message to a window or windows. 

 If the window was created by the calling thread, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> calls the window procedure for the window and does not return until the window procedure has processed the message. 

 If the window was created by a different thread, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> passes the message to the window procedure and returns immediately; it does not wait for the window procedure to finish processing the message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool SendNotifyMessage(
	IntPtr hWnd,
	uint msg,
	[OptionalAttribute] IntPtr wParam,
	[OptionalAttribute] IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function SendNotifyMessage ( 
	hWnd As IntPtr,
	msg As UInteger,
	<OptionalAttribute> wParam As IntPtr,
	<OptionalAttribute> lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim msg As UInteger
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SendNotifyMessage(hWnd, 
	msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool SendNotifyMessage(
	IntPtr hWnd, 
	unsigned int msg, 
	[OptionalAttribute] IntPtr wParam, 
	[OptionalAttribute] IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member SendNotifyMessage : 
        hWnd : IntPtr * 
        msg : uint32 * 
        [<OptionalAttribute>] wParam : IntPtr * 
        [<OptionalAttribute>] lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose window procedure will receive the message. 

 If this parameter is HWND_BROADCAST ((HWND)0xffff), the message is sent to all top-level windows in the system, including disabled or invisible unowned windows, overlapped windows, and pop-up windows; but the message is not sent to child windows.</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message to be sent. See <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WindowMessages</a>.</dd><dt>wParam (Optional)</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd><dt>lParam (Optional)</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-sendnotifymessagea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-sendnotifymessagea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />