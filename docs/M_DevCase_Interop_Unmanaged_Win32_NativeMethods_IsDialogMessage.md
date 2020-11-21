# NativeMethods.IsDialogMessage Method 
 

Determines whether a message is intended for the specified dialog box and, if it is, processes the message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static bool IsDialogMessage(
	IntPtr hDlg,
	ref NativeMessage refMsg
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function IsDialogMessage ( 
	hDlg As IntPtr,
	ByRef refMsg As NativeMessage
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDlg As IntPtr
Dim refMsg As NativeMessage
Dim returnValue As Boolean

returnValue = NativeMethods.IsDialogMessage(hDlg, 
	refMsg)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static bool IsDialogMessage(
	IntPtr hDlg, 
	NativeMessage% refMsg
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member IsDialogMessage : 
        hDlg : IntPtr * 
        refMsg : NativeMessage byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDlg</dt><dd>Type: System.IntPtr<br />A handle to the dialog box.</dd><dt>refMsg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">DevCase.Interop.Unmanaged.Win32.Structures.NativeMessage</a><br />A pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a> structure that contains the message to be checked.</dd></dl>

#### Return Value
Type: Boolean<br />If the message has been processed, the return value is `true` (`True` in Visual Basic). 

 If the message has not been processed, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-isdialogmessagea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-isdialogmessagea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />