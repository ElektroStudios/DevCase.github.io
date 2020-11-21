# NativeMethods.DefWindowProc Method 
 

Calls the default window procedure to provide default processing for any window messages that an application does not process. 

 This function ensures that every message is processed. 

DefWindowProc(IntPtr, UInt32, IntPtr, IntPtr) is called with the same parameters received by the window procedure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto)]
public static IntPtr DefWindowProc(
	IntPtr hWnd,
	uint msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto>]
Public Shared Function DefWindowProc ( 
	hWnd As IntPtr,
	msg As UInteger,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim msg As UInteger
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DefWindowProc(hWnd, 
	msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto)]
static IntPtr DefWindowProc(
	IntPtr hWnd, 
	unsigned int msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto)>]
static member DefWindowProc : 
        hWnd : IntPtr * 
        msg : uint32 * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window procedure that received the message.</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message to be processed.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value specifies the result of the message processing and depends on the message.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defwindowproca" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defwindowproca</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />