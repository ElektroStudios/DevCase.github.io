# NativeMethods.GetUpdateRgn Method (IntPtr, IntPtr, Boolean)
 

Retrieves the update region of a window by copying it into the specified region. 

 The coordinates of the update region are relative to the upper-left corner of the window (that is, they are client coordinates).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static RegionComplexity GetUpdateRgn(
	IntPtr hWnd,
	IntPtr hRgn,
	bool erase
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetUpdateRgn ( 
	hWnd As IntPtr,
	hRgn As IntPtr,
	erase As Boolean
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim hRgn As IntPtr
Dim erase As Boolean
Dim returnValue As RegionComplexity

returnValue = NativeMethods.GetUpdateRgn(hWnd, 
	hRgn, erase)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static RegionComplexity GetUpdateRgn(
	IntPtr hWnd, 
	IntPtr hRgn, 
	bool erase
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetUpdateRgn : 
        hWnd : IntPtr * 
        hRgn : IntPtr * 
        erase : bool -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window with an update region that is to be retrieved.</dd><dt>hRgn</dt><dd>Type: System.IntPtr<br />A handle to the region to receive the update region.</dd><dt>erase</dt><dd>Type: System.Boolean<br />\[Missing <param name="erase"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.GetUpdateRgn(System.IntPtr,System.IntPtr,System.Boolean)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value indicates the complexity of the resulting region. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getupdatergn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getupdatergn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetUpdateRgn">GetUpdateRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />