# NativeMethods.DefDlgProc Method 
 

Calls the default dialog box window procedure to provide default processing for any window messages that a dialog box with a private window class does not process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static IntPtr DefDlgProc(
	IntPtr hDlg,
	uint msg,
	IntPtr wParam,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function DefDlgProc ( 
	hDlg As IntPtr,
	msg As UInteger,
	wParam As IntPtr,
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hDlg As IntPtr
Dim msg As UInteger
Dim wParam As IntPtr
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DefDlgProc(hDlg, 
	msg, wParam, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static IntPtr DefDlgProc(
	IntPtr hDlg, 
	unsigned int msg, 
	IntPtr wParam, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member DefDlgProc : 
        hDlg : IntPtr * 
        msg : uint32 * 
        wParam : IntPtr * 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hDlg</dt><dd>Type: System.IntPtr<br />A handle to the dialog box.</dd><dt>msg</dt><dd>Type: System.UInt32<br />The message to be processed.</dd><dt>wParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Additional message information. The content of this parameter depends on the value of the *msg* parameter.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value specifies the result of the message processing and depends on the message.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defdlgprocw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defdlgprocw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />