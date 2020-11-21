# NativeMethods.EqualRgn Method 
 

Checks the two specified regions to determine whether they are identical. 

 The function considers two regions identical if they are equal in size and shape.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool EqualRgn(
	IntPtr hRgn1,
	IntPtr hRgn2
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function EqualRgn ( 
	hRgn1 As IntPtr,
	hRgn2 As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hRgn1 As IntPtr
Dim hRgn2 As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EqualRgn(hRgn1, 
	hRgn2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool EqualRgn(
	IntPtr hRgn1, 
	IntPtr hRgn2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member EqualRgn : 
        hRgn1 : IntPtr * 
        hRgn2 : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hRgn1</dt><dd>Type: System.IntPtr<br />Handle to a region.</dd><dt>hRgn2</dt><dd>Type: System.IntPtr<br />Handle to a region.</dd></dl>

#### Return Value
Type: Boolean<br />If the two regions are equal, the return value is `true` (`True` in Visual Basic). 

 If the two regions are not equal, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-equalrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-equalrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />