# NativeMethods.CreateEllipticRgnIndirect Method (Rectangle)
 

Creates an elliptical region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static IntPtr CreateEllipticRgnIndirect(
	ref Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function CreateEllipticRgnIndirect ( 
	ByRef refRect As Rectangle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateEllipticRgnIndirect(refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static IntPtr CreateEllipticRgnIndirect(
	Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member CreateEllipticRgnIndirect : 
        refRect : Rectangle byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that contains the coordinates of the upper-left and lower-right corners of the bounding rectangle of the ellipse in logical units.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the region. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createellipticrgnindirect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createellipticrgnindirect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateEllipticRgnIndirect">CreateEllipticRgnIndirect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />