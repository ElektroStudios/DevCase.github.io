# NativeMethods.GetWindowRgn Method (IntPtr, IntPtr)
 

Obtains a copy of the window region of a window. 

 The window region of a window is set by calling the SetWindowRgn function. 

 The window region determines the area within the window where the system permits drawing. 

 The system does not display any portion of a window that lies outside of the window region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static RegionComplexity GetWindowRgn(
	IntPtr hWnd,
	IntPtr hRgn
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowRgn ( 
	hWnd As IntPtr,
	hRgn As IntPtr
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim hRgn As IntPtr
Dim returnValue As RegionComplexity

returnValue = NativeMethods.GetWindowRgn(hWnd, 
	hRgn)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static RegionComplexity GetWindowRgn(
	IntPtr hWnd, 
	IntPtr hRgn
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowRgn : 
        hWnd : IntPtr * 
        hRgn : IntPtr -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose window region is to be obtained.</dd><dt>hRgn</dt><dd>Type: System.IntPtr<br />A handle to the region which will be modified to represent the window region.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value specifies the type of the region that the function obtains. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowRgn">GetWindowRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />