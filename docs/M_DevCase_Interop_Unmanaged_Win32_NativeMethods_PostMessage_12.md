# NativeMethods.PostMessage Method (SafeHandle, ListBoxMessages, IntPtr, IntPtr)
 

Places (posts) a message in the message queue associated with the thread that created the specified ListBox control and returns without waiting for the thread to process the message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool PostMessage(
	SafeHandle hWnd,
	ListBoxMessages message,
	IntPtr wparam,
	IntPtr lparam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function PostMessage ( 
	hWnd As SafeHandle,
	message As ListBoxMessages,
	wparam As IntPtr,
	lparam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim message As ListBoxMessages
Dim wparam As IntPtr
Dim lparam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.PostMessage(hWnd, 
	message, wparam, lparam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool PostMessage(
	SafeHandle^ hWnd, 
	ListBoxMessages message, 
	IntPtr wparam, 
	IntPtr lparam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member PostMessage : 
        hWnd : SafeHandle * 
        message : ListBoxMessages * 
        wparam : IntPtr * 
        lparam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />Handle to the window whose window procedure will receive the message. 

 If this parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">HWND_Broadcast</a>, the message is sent to all top-level windows in the system, including disabled or invisible unowned windows, overlapped windows, and pop-up windows; but the message is not sent to child windows.</dd><dt>message</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ListBoxMessages">DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages</a><br />Specifies the message to be sent.</dd><dt>wparam</dt><dd>Type: System.IntPtr<br />Specifies additional message-specific information.</dd><dt>lparam</dt><dd>Type: System.IntPtr<br />Specifies additional message-specific information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644944%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644944%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PostMessage">PostMessage Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />