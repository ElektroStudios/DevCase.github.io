# NativeMethods.ReplyMessage Method 
 

Replies to a message sent from another thread by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendMessage">SendMessage(IntPtr, EditControlMessages, IntPtr, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ReplyMessage(
	IntPtr result
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ReplyMessage ( 
	result As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim result As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ReplyMessage(result)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool ReplyMessage(
	IntPtr result
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member ReplyMessage : 
        result : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>result</dt><dd>Type: System.IntPtr<br />The result of the message processing. The possible values are based on the message sent.</dd></dl>

#### Return Value
Type: Boolean<br />If the calling thread was processing a message sent from another thread or process, the return value is `true` (`True` in Visual Basic). 

 If the calling thread was not processing a message sent from another thread or process, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-replymessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-replymessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />