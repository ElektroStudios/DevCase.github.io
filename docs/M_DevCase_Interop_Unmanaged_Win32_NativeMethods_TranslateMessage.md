# NativeMethods.TranslateMessage Method 
 

Translates virtual-key messages into character messages. The character messages are posted to the calling thread's message queue, to be read the next time the thread calls the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool TranslateMessage(
	out NativeMessage refMsg
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function TranslateMessage ( 
	<OutAttribute> ByRef refMsg As NativeMessage
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refMsg As NativeMessage
Dim returnValue As Boolean

returnValue = NativeMethods.TranslateMessage(refMsg)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool TranslateMessage(
	[InAttribute] [OutAttribute] NativeMessage% refMsg
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member TranslateMessage : 
        refMsg : NativeMessage byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refMsg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">DevCase.Interop.Unmanaged.Win32.Structures.NativeMessage</a><br />A pointer to a structure that contains message information retrieved from the calling thread's message queue by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessage">GetMessage(NativeMessage, IntPtr, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the message is translated (that is, a character message is posted to the thread's message queue), the return value is `true` (`True` in Visual Basic). 

 f the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyUp</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysKeyDown</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysKeyUp</a>, the return value is `true` (`True` in Visual Basic), regardless of the translation. 

 If the message is not translated (that is, a character message is not posted to the thread's message queue), the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-translatemessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-translatemessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />