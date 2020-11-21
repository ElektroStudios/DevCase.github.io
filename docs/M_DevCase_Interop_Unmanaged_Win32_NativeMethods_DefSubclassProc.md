# NativeMethods.DefSubclassProc Method (IntPtr, WindowMessages, IntPtr, IntPtr)
 

Calls the next handler in a window's subclass chain. 

 The last handler in the subclass chain calls the original window procedure for the window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", SetLastError = true)]
public static IntPtr DefSubclassProc(
	IntPtr hWnd,
	WindowMessages msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", SetLastError := true>]
Public Shared Function DefSubclassProc ( 
	hWnd As IntPtr,
	msg As WindowMessages,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim msg As WindowMessages
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DefSubclassProc(hWnd, 
	msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", SetLastError = true)]
static IntPtr DefSubclassProc(
	IntPtr hWnd, 
	WindowMessages msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", SetLastError = true)>]
static member DefSubclassProc : 
        hWnd : IntPtr * 
        msg : WindowMessages * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window being subclassed.</dd><dt>msg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">DevCase.Interop.Unmanaged.Win32.Enums.WindowMessages</a><br />A window message.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Specifies additional message information. The contents of this parameter depend on the value of the window message.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Specifies additional message information. The contents of this parameter depend on the value of the window message. 

 Note: On 64-bit versions of Windows *lParam* is a 64-bit value.</dd></dl>

#### Return Value
Type: IntPtr<br />The returned value is specific to the message sent. This value should be ignored.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-defsubclassproc" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-defsubclassproc</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DefSubclassProc">DefSubclassProc Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />