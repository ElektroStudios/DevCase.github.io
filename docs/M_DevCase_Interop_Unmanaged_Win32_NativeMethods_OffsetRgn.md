# NativeMethods.OffsetRgn Method 
 

Moves a region by the specified offsets.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static RegionComplexity OffsetRgn(
	IntPtr hRgn,
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function OffsetRgn ( 
	hRgn As IntPtr,
	x As Integer,
	y As Integer
) As RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim hRgn As IntPtr
Dim x As Integer
Dim y As Integer
Dim returnValue As RegionComplexity

returnValue = NativeMethods.OffsetRgn(hRgn, 
	x, y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static RegionComplexity OffsetRgn(
	IntPtr hRgn, 
	int x, 
	int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member OffsetRgn : 
        hRgn : IntPtr * 
        x : int * 
        y : int -> RegionComplexity 

```


#### Parameters
&nbsp;<dl><dt>hRgn</dt><dd>Type: System.IntPtr<br />Handle to the region to be moved.</dd><dt>x</dt><dd>Type: System.Int32<br />Specifies the number of logical units to move left or right.</dd><dt>y</dt><dd>Type: System.Int32<br />Specifies the number of logical units to move up or down.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">RegionComplexity</a><br />The return value specifies the new region's complexity. 

 If the *hRgn* parameter does not identify a valid region, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegionComplexity">Error</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-offsetrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-offsetrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />