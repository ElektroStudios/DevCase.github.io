# NativeMethods.OpenClipboard Method 
 

Opens the clipboard for examination and prevents other applications from modifying the clipboard content.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool OpenClipboard(
	IntPtr hWndNewOwner
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function OpenClipboard ( 
	hWndNewOwner As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWndNewOwner As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.OpenClipboard(hWndNewOwner)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool OpenClipboard(
	IntPtr hWndNewOwner
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member OpenClipboard : 
        hWndNewOwner : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWndNewOwner</dt><dd>Type: System.IntPtr<br />A handle to the window to be associated with the open clipboard. 

 If this parameter is Zero, the open clipboard is associated with the current task.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-openclipboard" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-openclipboard</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />