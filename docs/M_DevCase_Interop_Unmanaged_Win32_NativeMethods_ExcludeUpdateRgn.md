# NativeMethods.ExcludeUpdateRgn Method (IntPtr, IntPtr)
 

prevents drawing within invalid areas of a window by excluding an updated region in the window from a clipping region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static RegionComplexity ExcludeUpdateRgn(
	IntPtr hDC,
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ExcludeUpdateRgn ( 
	hDC As IntPtr,
	hWnd As IntPtr
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hDC As IntPtr
Dim hWnd As IntPtr
Dim returnValue As RegionComplexity

returnValue = NativeMethods.ExcludeUpdateRgn(hDC, 
	hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static RegionComplexity ExcludeUpdateRgn(
	IntPtr hDC, 
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ExcludeUpdateRgn : 
        hDC : IntPtr * 
        hWnd : IntPtr -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hDC</dt><dd>Type: System.IntPtr<br />A handle to the device context associated with the clipping region.</dd><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to update.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value specifies the complexity of the excluded region. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-excludeupdatergn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-excludeupdatergn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ExcludeUpdateRgn">ExcludeUpdateRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />