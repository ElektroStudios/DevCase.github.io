# NativeMethods.GetMessage Method 
 

Retrieves a message from the calling thread's message queue. 

 The function dispatches incoming sent messages until a posted message is available for retrieval. 

 Unlike GetMessage(NativeMessage, IntPtr, UInt32, UInt32), the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> function does not wait for a message to be posted before returning.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool GetMessage(
	out NativeMessage refMsg,
	[OptionalAttribute] IntPtr hWnd,
	[OptionalAttribute] uint msgFilterMin,
	[OptionalAttribute] uint msgFilterMax
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function GetMessage ( 
	<OutAttribute> ByRef refMsg As NativeMessage,
	<OptionalAttribute> hWnd As IntPtr,
	<OptionalAttribute> msgFilterMin As UInteger,
	<OptionalAttribute> msgFilterMax As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refMsg As NativeMessage
Dim hWnd As IntPtr
Dim msgFilterMin As UInteger
Dim msgFilterMax As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetMessage(refMsg, 
	hWnd, msgFilterMin, msgFilterMax)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool GetMessage(
	[OutAttribute] NativeMessage% refMsg, 
	[OptionalAttribute] IntPtr hWnd, 
	[OptionalAttribute] unsigned int msgFilterMin, 
	[OptionalAttribute] unsigned int msgFilterMax
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member GetMessage : 
        refMsg : NativeMessage byref * 
        [<OptionalAttribute>] hWnd : IntPtr * 
        [<OptionalAttribute>] msgFilterMin : uint32 * 
        [<OptionalAttribute>] msgFilterMax : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>refMsg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">DevCase.Interop.Unmanaged.Win32.Structures.NativeMessage</a><br />A pointer to a structure that receives message information from the thread's message queue.</dd><dt>hWnd (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the window whose messages are to be retrieved. The window must belong to the current thread. 

 If *hWnd* is Zero, GetMessage(NativeMessage, IntPtr, UInt32, UInt32) retrieves messages for any window that belongs to the current thread, and any messages on the current thread's message queue whose <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage_Hwnd">Hwnd</a> value is Zero. Therefore if *hWnd* is Zero, both window messages and thread messages are processed. 

 If *hWnd* is -1, GetMessage(NativeMessage, IntPtr, UInt32, UInt32) retrieves only messages on the current thread's message queue whose <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage_Hwnd">Hwnd</a> value is Zero, that is, thread messages as posted by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PostMessage">PostMessage(IntPtr, EditControlMessages, IntPtr, IntPtr)</a> (when the hWnd parameter is Zero) or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PostThreadMessage">PostThreadMessage(Int32, WindowMessages, IntPtr, IntPtr)</a>.</dd><dt>msgFilterMin (Optional)</dt><dd>Type: System.UInt32<br />The integer value of the lowest message value to be retrieved. Use <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyFirst</a> to specify the first keyboard message or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseFirst</a> to specify the first mouse message. 

 Use <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Input</a> here and in *msgFilterMax* to specify only the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Input</a> messages. 

 If *msgFilterMin* and *msgFilterMax* are both zero, GetMessage(NativeMessage, IntPtr, UInt32, UInt32) returns all available messages (that is, no range filtering is performed).</dd><dt>msgFilterMax (Optional)</dt><dd>Type: System.UInt32<br />The integer value of the highest message value to be retrieved. Use <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyLast</a> to specify the last keyboard message or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseLast</a> to specify the last mouse message. 

 Use <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Input</a> here and in *msgFilterMin* to specify only the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Input</a> messages. 

 If *msgFilterMin* and *msgFilterMax* are both zero, GetMessage(NativeMessage, IntPtr, UInt32, UInt32) returns all available messages (that is, no range filtering is performed).</dd></dl>

#### Return Value
Type: Boolean<br />If the function retrieves a message other than <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Quit</a>, the return value is `true` (`True` in Visual Basic). 

 If the function retrieves the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Quit</a> message, the return value is `false` (`False` in Visual Basic). 

 If there is an error, the return value is -1. For example, the function fails if *hWnd* is an invalid window handle or *refMsg* is an invalid pointer. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />