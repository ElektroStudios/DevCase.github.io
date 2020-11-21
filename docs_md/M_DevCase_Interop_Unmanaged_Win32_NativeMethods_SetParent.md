# NativeMethods.SetParent Method 
 

Changes the parent window of the specified child window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr SetParent(
	IntPtr hWndChild,
	IntPtr hWndNewParent
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetParent ( 
	hWndChild As IntPtr,
	hWndNewParent As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWndChild As IntPtr
Dim hWndNewParent As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SetParent(hWndChild, 
	hWndNewParent)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr SetParent(
	IntPtr hWndChild, 
	IntPtr hWndNewParent
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetParent : 
        hWndChild : IntPtr * 
        hWndNewParent : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWndChild</dt><dd>Type: System.IntPtr<br />A handle to the child window.</dd><dt>hWndNewParent</dt><dd>Type: System.IntPtr<br />A handle to the new parent window. If this parameter is Zero, the desktop window becomes the new parent window. 

 If this parameter is HWND_MESSAGE, the child window becomes a message-only window.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setparent" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setparent</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />