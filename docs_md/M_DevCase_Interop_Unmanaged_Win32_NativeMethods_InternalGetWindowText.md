# NativeMethods.InternalGetWindowText Method 
 

Copies the text of the specified window's title bar (if it has one) into a buffer. 

 This function is similar to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowText">GetWindowText(IntPtr, StringBuilder, Int32)</a> function. However, it obtains the window text directly from the window structure associated with the specified window's handle and then always provides the text as a Unicode string. 

 This is unlike <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowText">GetWindowText(IntPtr, StringBuilder, Int32)</a> which obtains the text by sending the window a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_GetText</a> message. 

 If the specified window is a control, the text of the control is obtained.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int InternalGetWindowText(
	IntPtr hWnd,
	StringBuilder buffer,
	int maxCount
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function InternalGetWindowText ( 
	hWnd As IntPtr,
	buffer As StringBuilder,
	maxCount As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim buffer As StringBuilder
Dim maxCount As Integer
Dim returnValue As Integer

returnValue = NativeMethods.InternalGetWindowText(hWnd, 
	buffer, maxCount)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int InternalGetWindowText(
	IntPtr hWnd, 
	StringBuilder^ buffer, 
	int maxCount
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member InternalGetWindowText : 
        hWnd : IntPtr * 
        buffer : StringBuilder * 
        maxCount : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window or control containing the text.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />The buffer that is to receive the text.</dd><dt>maxCount</dt><dd>Type: System.Int32<br />The maximum number of characters to be copied to the buffer, including the null character. 

 If the text exceeds this limit, it is truncated</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the length, in characters, of the copied string, not including the terminating null character. 

 If the window has no title bar or text, if the title bar is empty, or if the window or control handle is invalid, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-internalgetwindowtext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-internalgetwindowtext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />