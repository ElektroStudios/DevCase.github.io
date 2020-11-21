# NativeMethods.RectInRegion Method (IntPtr, NativeRectangle)
 

Determines whether any part of the specified rectangle is within the boundaries of a region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool RectInRegion(
	IntPtr hRgn,
	ref NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function RectInRegion ( 
	hRgn As IntPtr,
	ByRef refRect As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hRgn As IntPtr
Dim refRect As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.RectInRegion(hRgn, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool RectInRegion(
	IntPtr hRgn, 
	NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member RectInRegion : 
        hRgn : IntPtr * 
        refRect : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hRgn</dt><dd>Type: System.IntPtr<br />Handle to the region.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure containing the coordinates of the rectangle in logical units. 

 The lower and right edges of the rectangle are not included.</dd></dl>

#### Return Value
Type: Boolean<br />If any part of the specified rectangle lies within the boundaries of the region, the return value is `true` (`True` in Visual Basic). 

 If no part of the specified rectangle lies within the boundaries of the region, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-rectinregion" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-rectinregion</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RectInRegion">RectInRegion Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />