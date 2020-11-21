# NativeMethods.GetInputState Method 
 

Determines whether there are mouse-button or keyboard messages in the calling thread's message queue.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool GetInputState()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetInputState As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.GetInputState()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool GetInputState()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetInputState : unit -> bool 

```


#### Return Value
Type: Boolean<br />If the queue contains one or more new mouse-button or keyboard messages, the return value is `true` (`True` in Visual Basic). 

 If there are no new mouse-button or keyboard messages in the queue, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644935(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644935(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />