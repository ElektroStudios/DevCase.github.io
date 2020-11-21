# NativeMethods.PeekMessage Method 
 

Dispatches incoming sent messages, checks the thread message queue for a posted message, and retrieves the message (if any exist).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto)]
public static bool PeekMessage(
	out NativeMessage refMsg,
	[OptionalAttribute] IntPtr hWnd,
	[OptionalAttribute] uint msgFilterMin,
	[OptionalAttribute] uint msgFilterMax,
	[OptionalAttribute] PeekMessageFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto>]
Public Shared Function PeekMessage ( 
	<OutAttribute> ByRef refMsg As NativeMessage,
	<OptionalAttribute> hWnd As IntPtr,
	<OptionalAttribute> msgFilterMin As UInteger,
	<OptionalAttribute> msgFilterMax As UInteger,
	<OptionalAttribute> flags As PeekMessageFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refMsg As NativeMessage
Dim hWnd As IntPtr
Dim msgFilterMin As UInteger
Dim msgFilterMax As UInteger
Dim flags As PeekMessageFlags
Dim returnValue As Boolean

returnValue = NativeMethods.PeekMessage(refMsg, 
	hWnd, msgFilterMin, msgFilterMax, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto)]
static bool PeekMessage(
	[OutAttribute] NativeMessage% refMsg, 
	[OptionalAttribute] IntPtr hWnd, 
	[OptionalAttribute] unsigned int msgFilterMin, 
	[OptionalAttribute] unsigned int msgFilterMax, 
	[OptionalAttribute] PeekMessageFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto)>]
static member PeekMessage : 
        refMsg : NativeMessage byref * 
        [<OptionalAttribute>] hWnd : IntPtr * 
        [<OptionalAttribute>] msgFilterMin : uint32 * 
        [<OptionalAttribute>] msgFilterMax : uint32 * 
        [<OptionalAttribute>] flags : PeekMessageFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>refMsg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">DevCase.Interop.Unmanaged.Win32.Structures.NativeMessage</a><br />A pointer to a structure that receives message information.</dd><dt>hWnd (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the window whose messages are to be retrieved. The window must belong to the current thread. 

 If *hWnd* is Zero, PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags) retrieves messages for any window that belongs to the current thread, and any messages on the current thread's message queue whose <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage_Hwnd">Hwnd</a> value is Zero. Therefore if *hWnd* is Zero, both window messages and thread messages are processed. 

 If *hWnd* is -1, PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags) retrieves only messages on the current thread's message queue whose <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage_Hwnd">Hwnd</a> value is Zero, that is, thread messages as posted by PostMessage (when the *hWnd* parameter is Zero) or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PostThreadMessage">PostThreadMessage(Int32, WindowMessages, IntPtr, IntPtr)</a>.</dd><dt>msgFilterMin (Optional)</dt><dd>Type: System.UInt32<br />The value of the first message in the range of messages to be examined. Use <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyFirst</a> to specify the first keyboard message or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseFirst</a> to specify the first mouse message. 

 If *msgFilterMin* and *msgFilterMax* are both zero, PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags) returns all available messages (that is, no range filtering is performed).</dd><dt>msgFilterMax (Optional)</dt><dd>Type: System.UInt32<br />The value of the last message in the range of messages to be examined. Use <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyLast</a> to specify the last keyboard message or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseLast</a> to specify the last mouse message. 

 If *msgFilterMin* and *msgFilterMax* are both zero, PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags) returns all available messages (that is, no range filtering is performed).</dd><dt>flags (Optional)</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PeekMessageFlags">DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags</a><br />Specifies how messages are to be handled.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-peekmessagea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-peekmessagea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />