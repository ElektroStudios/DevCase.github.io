# NativeMethods.SendMessageTimeout Method (SafeHandle, WindowMessages, IntPtr, IntPtr, SendMessageTimeoutFlags, Int32, IntPtr)
 

Sends the specified message to a window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr SendMessageTimeout(
	SafeHandle hWnd,
	WindowMessages msg,
	IntPtr wParam,
	IntPtr lParam,
	SendMessageTimeoutFlags fuFlags,
	int uTimeout,
	out IntPtr refResult
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SendMessageTimeout ( 
	hWnd As SafeHandle,
	msg As WindowMessages,
	wParam As IntPtr,
	lParam As IntPtr,
	fuFlags As SendMessageTimeoutFlags,
	uTimeout As Integer,
	<OutAttribute> ByRef refResult As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim msg As WindowMessages
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim fuFlags As SendMessageTimeoutFlags
Dim uTimeout As Integer
Dim refResult As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SendMessageTimeout(hWnd, 
	msg, wParam, lParam, fuFlags, uTimeout, 
	refResult)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr SendMessageTimeout(
	SafeHandle^ hWnd, 
	WindowMessages msg, 
	IntPtr wParam, 
	IntPtr lParam, 
	SendMessageTimeoutFlags fuFlags, 
	int uTimeout, 
	[OutAttribute] IntPtr% refResult
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SendMessageTimeout : 
        hWnd : SafeHandle * 
        msg : WindowMessages * 
        wParam : IntPtr * 
        lParam : IntPtr * 
        fuFlags : SendMessageTimeoutFlags * 
        uTimeout : int * 
        refResult : IntPtr byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose window procedure will receive the message. 

 If this parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">HWND_Broadcast</a>, the message is sent to all top-level windows in the system, including disabled or invisible unowned windows. 

 The function does not return until each window has timed out. Therefore, the total wait time can be up to the value of uTimeout multiplied by the number of top-level windows.</dd><dt>msg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages</a><br />The message to be sent. 

 For lists of the system-provided messages, see System-Defined Messages: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927%28v=vs.85%29.aspx#system_defined" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927%28v=vs.85%29.aspx#system_defined</a></dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Any additional message-specific information.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Any additional message-specific information.</dd><dt>fuFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SendMessageTimeoutFlags">DevCase.Interop.Unmanaged.Win32.Enums.SendMessageTimeoutFlags</a><br />The behavior of this function.</dd><dt>uTimeout</dt><dd>Type: System.Int32<br />The duration of the time-out period, in milliseconds. 

 If the message is a broadcast message, each window can use the full time-out period. 

 For example, if you specify a five second time-out period and there are three top-level windows that fail to process the message, you could have up to a 15 second delay.</dd><dt>refResult</dt><dd>Type: System.IntPtr<br />The result of the message processing. 

 The value of this parameter depends on the message that is specified.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is nonzero. If the function fails or times out, the return value is Zero. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendMessageTimeout">SendMessageTimeout(IntPtr, EditControlMessages, IntPtr, IntPtr, SendMessageTimeoutFlags, Int32, IntPtr)</a> does not provide information about individual windows timing out if <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">HWND_Broadcast</a> is used. 

 To get extended error information, call GetLastWin32Error(). If GetLastWin32Error() returns `ERROR_TIMEOUT`, then the function timed out.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644952%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644952%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendMessageTimeout">SendMessageTimeout Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />