# NativeMethods.CombineRgn Method 
 

Combines two regions and stores the result in a third region. 

 The two regions are combined according to the specified mode.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static RegionComplexity CombineRgn(
	IntPtr hRgnDst,
	IntPtr hRgnSrc1,
	IntPtr hRgnSrc2,
	RegionCombineMode mode
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function CombineRgn ( 
	hRgnDst As IntPtr,
	hRgnSrc1 As IntPtr,
	hRgnSrc2 As IntPtr,
	mode As RegionCombineMode
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hRgnDst As IntPtr
Dim hRgnSrc1 As IntPtr
Dim hRgnSrc2 As IntPtr
Dim mode As RegionCombineMode
Dim returnValue As RegionComplexity

returnValue = NativeMethods.CombineRgn(hRgnDst, 
	hRgnSrc1, hRgnSrc2, mode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static RegionComplexity CombineRgn(
	IntPtr hRgnDst, 
	IntPtr hRgnSrc1, 
	IntPtr hRgnSrc2, 
	RegionCombineMode mode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member CombineRgn : 
        hRgnDst : IntPtr * 
        hRgnSrc1 : IntPtr * 
        hRgnSrc2 : IntPtr * 
        mode : RegionCombineMode -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hRgnDst</dt><dd>Type: System.IntPtr<br />A handle to a new region with dimensions defined by combining two other regions. 

 (This region must exist before CombineRgn(IntPtr, IntPtr, IntPtr, RegionCombineMode) is called.)</dd><dt>hRgnSrc1</dt><dd>Type: System.IntPtr<br />A handle to the first of two regions to be combined.</dd><dt>hRgnSrc2</dt><dd>Type: System.IntPtr<br />A handle to the second of two regions to be combined.</dd><dt>mode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionCombineMode">DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode</a><br />A mode indicating how the two regions will be combined.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value specifies the type of the resulting region. 

 If the *hRgnDst*, *hRgnSrc1* or *hRgnSrc2* parameters does not identify a valid region, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">Error</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-combinergn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-combinergn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />