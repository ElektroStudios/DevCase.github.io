# NativeMethods.PtInRegion Method (SafeHandle, Int32, Int32)
 

Determines whether the specified point is inside the specified region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool PtInRegion(
	SafeHandle hrgn,
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function PtInRegion ( 
	hrgn As SafeHandle,
	x As Integer,
	y As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hrgn As SafeHandle
Dim x As Integer
Dim y As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.PtInRegion(hrgn, 
	x, y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool PtInRegion(
	SafeHandle^ hrgn, 
	int x, 
	int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member PtInRegion : 
        hrgn : SafeHandle * 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>hrgn</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A Handle to the region to be examined.</dd><dt>x</dt><dd>Type: System.Int32<br />The x-coordinate of the point in logical units.</dd><dt>y</dt><dd>Type: System.Int32<br />The y-coordinate of the point in logical units.</dd></dl>

#### Return Value
Type: Boolean<br />If the specified point is in the region, the return value is `true` (`True` in Visual Basic). 

 If the specified point is not in the region, the return value is `false` (`False` in Visual Basic)

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162883%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162883%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PtInRegion">PtInRegion Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />