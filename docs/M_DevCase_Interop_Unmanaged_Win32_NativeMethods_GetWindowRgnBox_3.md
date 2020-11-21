# NativeMethods.GetWindowRgnBox Method (SafeHandle, Rectangle)
 

Retrieves the dimensions of the tightest bounding rectangle for the window region of a window..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static RegionComplexity GetWindowRgnBox(
	SafeHandle hWnd,
	ref Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowRgnBox ( 
	hWnd As SafeHandle,
	ByRef refRect As Rectangle
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refRect As Rectangle
Dim returnValue As RegionComplexity

returnValue = NativeMethods.GetWindowRgnBox(hWnd, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static RegionComplexity GetWindowRgnBox(
	SafeHandle^ hWnd, 
	Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowRgnBox : 
        hWnd : SafeHandle * 
        refRect : Rectangle byref -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that receives the rectangle dimensions, in device units relative to the upper-left corner of the window.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value specifies the type of the region that the function obtains. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowrgnbox" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowrgnbox</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowRgnBox">GetWindowRgnBox Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />