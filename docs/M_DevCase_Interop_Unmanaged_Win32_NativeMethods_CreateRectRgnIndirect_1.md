# NativeMethods.CreateRectRgnIndirect Method (Rectangle)
 

Creates a rectangular region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static IntPtr CreateRectRgnIndirect(
	in Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function CreateRectRgnIndirect ( 
	ByRef refRect As Rectangle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateRectRgnIndirect(refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static IntPtr CreateRectRgnIndirect(
	[InAttribute] Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member CreateRectRgnIndirect : 
        refRect : Rectangle byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the coordinates of the upper-left and lower-right corners of the rectangle that defines the region in logical units.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the region. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183515(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183515(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateRectRgnIndirect">CreateRectRgnIndirect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />