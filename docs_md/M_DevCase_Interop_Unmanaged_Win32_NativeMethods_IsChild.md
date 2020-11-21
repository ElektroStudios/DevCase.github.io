# NativeMethods.IsChild Method 
 

Determines whether a window is a child window or descendant window of a specified parent window. 

 A child window is the direct descendant of a specified parent window if that parent window is in the chain of parent windows; the chain of parent windows leads from the original overlapped or pop-up window to the child window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool IsChild(
	IntPtr hWndParent,
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function IsChild ( 
	hWndParent As IntPtr,
	hWnd As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWndParent As IntPtr
Dim hWnd As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.IsChild(hWndParent, 
	hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool IsChild(
	IntPtr hWndParent, 
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member IsChild : 
        hWndParent : IntPtr * 
        hWnd : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWndParent</dt><dd>Type: System.IntPtr<br />A handle to the parent window.</dd><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to be tested.</dd></dl>

#### Return Value
Type: Boolean<br />If the window is a child or descendant window of the specified parent window, the return value is `true` (`True` in Visual Basic). 

 If the window is not a child or descendant window of the specified parent window, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-ischild" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-ischild</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />