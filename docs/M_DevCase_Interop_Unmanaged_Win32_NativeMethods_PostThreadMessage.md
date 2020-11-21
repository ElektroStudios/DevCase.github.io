# NativeMethods.PostThreadMessage Method (Int32, WindowMessages, IntPtr, IntPtr)
 

Places (posts) a message to the message queue of the specified thread. 

 It returns without waiting for the thread to process the message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool PostThreadMessage(
	int threadId,
	WindowMessages message,
	IntPtr wparam,
	IntPtr lparam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function PostThreadMessage ( 
	threadId As Integer,
	message As WindowMessages,
	wparam As IntPtr,
	lparam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim threadId As Integer
Dim message As WindowMessages
Dim wparam As IntPtr
Dim lparam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.PostThreadMessage(threadId, 
	message, wparam, lparam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool PostThreadMessage(
	int threadId, 
	WindowMessages message, 
	IntPtr wparam, 
	IntPtr lparam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member PostThreadMessage : 
        threadId : int * 
        message : WindowMessages * 
        wparam : IntPtr * 
        lparam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>threadId</dt><dd>Type: System.Int32<br />The identifier of the thread to which the message is to be posted. 

 The function fails if the specified thread does not have a message queue. The system creates a thread's message queue when the thread makes its first call to one of the User or GDI functions. 

 Message posting is subject to UIPI. The thread of a process can post messages only to posted-message queues of threads in processes of lesser or equal integrity level. 

 This thread must have the `SE_TCB_NAME` privilege to post a message to a thread that belongs to a process with the same locally unique identifier (LUID) but is in a different desktop. Otherwise, the function fails and returns `ERROR_INVALID_THREAD_ID`.</dd><dt>message</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages</a><br />The type of message to be posted.</dd><dt>wparam</dt><dd>Type: System.IntPtr<br />Specifies additional message-specific information.</dd><dt>lparam</dt><dd>Type: System.IntPtr<br />Specifies additional message-specific information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644946%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644946%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PostThreadMessage">PostThreadMessage Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />