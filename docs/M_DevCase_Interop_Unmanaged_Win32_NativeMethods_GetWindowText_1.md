# NativeMethods.GetWindowText Method (SafeHandle, StringBuilder, Int32)
 

Copies the text of the specified window's title bar (if it has one) into a buffer. 

 If the specified window is a control, the text of the control is copied. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowText">GetWindowText(IntPtr, StringBuilder, Int32)</a> cannot retrieve the text of a control in another application than the calling application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int GetWindowText(
	SafeHandle hWnd,
	StringBuilder lpString,
	int cch
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetWindowText ( 
	hWnd As SafeHandle,
	lpString As StringBuilder,
	cch As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim lpString As StringBuilder
Dim cch As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetWindowText(hWnd, 
	lpString, cch)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int GetWindowText(
	SafeHandle^ hWnd, 
	StringBuilder^ lpString, 
	int cch
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetWindowText : 
        hWnd : SafeHandle * 
        lpString : StringBuilder * 
        cch : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window or control containing the text.</dd><dt>lpString</dt><dd>Type: System.Text.StringBuilder<br />The buffer that will receive the text. 

 If the string is as long or longer than the buffer, the string is truncated and terminated with a null character.</dd><dt>cch</dt><dd>Type: System.Int32<br />The maximum number of characters to copy to the buffer, including the null character. 

 If the text exceeds this limit, it is truncated.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the length, in characters, of the copied string, not including the terminating null character. 

 If the window has no title bar or text, if the title bar is empty, or if the window or control handle is invalid, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633520%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633520%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowText">GetWindowText Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />