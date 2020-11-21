# NativeMethods.SendMessage Method (IntPtr, ListViewMessages, IntPtr, IntPtr)
 

Sends the specified message to a ListView control. 

 The SendMessage function calls the window procedure for the specified window and does not return until the window procedure has processed the message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr SendMessage(
	IntPtr hWnd,
	ListViewMessages msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SendMessage ( 
	hWnd As IntPtr,
	msg As ListViewMessages,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim msg As ListViewMessages
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SendMessage(hWnd, 
	msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr SendMessage(
	IntPtr hWnd, 
	ListViewMessages msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SendMessage : 
        hWnd : IntPtr * 
        msg : ListViewMessages * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose window procedure will receive the message.</dd><dt>msg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ListViewMessages">DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages</a><br />The message to be sent.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Additional message-specific information.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value specifies the result of the message processing; it depends on the message sent.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644950%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644950%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendMessage">SendMessage Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />