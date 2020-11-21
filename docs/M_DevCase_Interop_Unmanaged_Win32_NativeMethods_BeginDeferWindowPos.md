# NativeMethods.BeginDeferWindowPos Method 
 

Allocates memory for a multiple-window- position structure and returns the handle to the structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr BeginDeferWindowPos(
	int numWindows
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function BeginDeferWindowPos ( 
	numWindows As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim numWindows As Integer
Dim returnValue As IntPtr

returnValue = NativeMethods.BeginDeferWindowPos(numWindows)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr BeginDeferWindowPos(
	int numWindows
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member BeginDeferWindowPos : 
        numWindows : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>numWindows</dt><dd>Type: System.Int32<br />The initial number of windows for which to store position information. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeferWindowPos">DeferWindowPos(IntPtr, IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags)</a> function increases the size of the structure, if necessary.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value identifies the multiple-window-position structure. 

 If insufficient system resources are available to allocate the structure, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-begindeferwindowpos" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-begindeferwindowpos</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />