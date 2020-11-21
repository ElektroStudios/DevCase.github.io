# NativeMethods.GetQueueStatus Method 
 

Retrieves the type of messages found in the calling thread's message queue.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static uint GetQueueStatus(
	QueueStatusFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetQueueStatus ( 
	flags As QueueStatusFlags
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim flags As QueueStatusFlags
Dim returnValue As UInteger

returnValue = NativeMethods.GetQueueStatus(flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static unsigned int GetQueueStatus(
	QueueStatusFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetQueueStatus : 
        flags : QueueStatusFlags -> uint32 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_QueueStatusFlags">DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags</a><br />Specifies the types of messages for which to check.</dd></dl>

#### Return Value
Type: UInt32<br />The high-order word of the return value indicates the types of messages currently in the queue. 

 The low-order word indicates the types of messages that have been added to the queue and that are still in the queue since the last call to the GetQueueStatus(QueueStatusFlags), <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> function.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getqueuestatus" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getqueuestatus</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />