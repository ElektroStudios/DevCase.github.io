# NativeMethods.GetRgnBox Method (IntPtr, Rectangle)
 

Retrieves the bounding rectangle of the specified region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static RegionComplexity GetRgnBox(
	IntPtr hRgn,
	out Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function GetRgnBox ( 
	hRgn As IntPtr,
	<OutAttribute> ByRef refRect As Rectangle
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hRgn As IntPtr
Dim refRect As Rectangle
Dim returnValue As RegionComplexity

returnValue = NativeMethods.GetRgnBox(hRgn, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static RegionComplexity GetRgnBox(
	IntPtr hRgn, 
	[OutAttribute] Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member GetRgnBox : 
        hRgn : IntPtr * 
        refRect : Rectangle byref -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hRgn</dt><dd>Type: System.IntPtr<br />A handle to the region.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that receives the bounding rectangle in logical units.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value specifies the region's complexity. 

 If the *hRgn* parameter does not identify a valid region, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">Error</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-getrgnbox" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-getrgnbox</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRgnBox">GetRgnBox Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />