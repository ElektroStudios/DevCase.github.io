# NativeMethods.GetMessagePos Method 
 

Retrieves the cursor position for the last message retrieved by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> function. 

 To determine the current position of the cursor, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCursorPos">GetCursorPos(NativePoint)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static uint GetMessagePos()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetMessagePos As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetMessagePos()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static unsigned int GetMessagePos()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetMessagePos : unit -> uint32 

```


#### Return Value
Type: UInt32<br />The return value specifies the x- and y-coordinates of the cursor position. 

 The x-coordinate is the low order short and the y-coordinate is the high-order short.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmessagepos" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmessagepos</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />