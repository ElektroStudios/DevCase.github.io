# NativeMethods.MapWindowPoints Method (SafeHandle, SafeHandle, NativeRectangle, UInt32)
 

Converts (maps) a set of points from a coordinate space relative to one window to a coordinate space relative to another window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int MapWindowPoints(
	SafeHandle hWndFrom,
	SafeHandle hWndTo,
	out NativeRectangle refRect,
	uint cPoints = 2
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function MapWindowPoints ( 
	hWndFrom As SafeHandle,
	hWndTo As SafeHandle,
	<OutAttribute> ByRef refRect As NativeRectangle,
	Optional cPoints As UInteger = 2
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWndFrom As SafeHandle
Dim hWndTo As SafeHandle
Dim refRect As NativeRectangle
Dim cPoints As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.MapWindowPoints(hWndFrom, 
	hWndTo, refRect, cPoints)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int MapWindowPoints(
	SafeHandle^ hWndFrom, 
	SafeHandle^ hWndTo, 
	[InAttribute] [OutAttribute] NativeRectangle% refRect, 
	unsigned int cPoints = 2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member MapWindowPoints : 
        hWndFrom : SafeHandle * 
        hWndTo : SafeHandle * 
        refRect : NativeRectangle byref * 
        ?cPoints : uint32 
(* Defaults:
        let _cPoints = defaultArg cPoints 2
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>hWndFrom</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window from which points are converted. 

 If this parameter is Zero or `HWND_DESKTOP`, the points are presumed to be in screen coordinates.</dd><dt>hWndTo</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window to which points are converted. 

 If this parameter is Zero or `HWND_DESKTOP`, the points are converted to screen coordinates.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure, in which case the cPoints parameter should be set to 2.</dd><dt>cPoints (Optional)</dt><dd>Type: System.UInt32<br />The number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structures in the array pointed to by the *refRect* parameter. 

 This value should be always `2UI`.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the low-order word of the return value is the number of pixels added to the horizontal coordinate of each source point in order to compute the horizontal coordinate of each destination point. 

 (In addition to that, if precisely one of *hwndFrom* and *hwndTo* is mirrored, then each resulting horizontal coordinate is multiplied by -1.) 

 The high-order word is the number of pixels added to the vertical coordinate of each source point in order to compute the vertical coordinate of each destination point. 



 If the function fails, the return value is `0`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145046%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145046%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MapWindowPoints">MapWindowPoints Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />