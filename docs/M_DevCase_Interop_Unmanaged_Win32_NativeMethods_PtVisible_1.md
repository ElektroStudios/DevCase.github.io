# NativeMethods.PtVisible Method (SafeHandle, Int32, Int32)
 

Determines whether the specified point is within the clipping region of a device context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static int PtVisible(
	SafeHandle hdc,
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function PtVisible ( 
	hdc As SafeHandle,
	x As Integer,
	y As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim x As Integer
Dim y As Integer
Dim returnValue As Integer

returnValue = NativeMethods.PtVisible(hdc, 
	x, y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static int PtVisible(
	SafeHandle^ hdc, 
	int x, 
	int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member PtVisible : 
        hdc : SafeHandle * 
        x : int * 
        y : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the device context (DC).</dd><dt>x</dt><dd>Type: System.Int32<br />The x-coordinate, in logical units, of the point.</dd><dt>y</dt><dd>Type: System.Int32<br />The y-coordinate, in logical units, of the point.</dd></dl>

#### Return Value
Type: Int32<br />If the specified point is within the clipping region of the device context, the return value is `1`. 

 If the specified point is not within the clipping region of the device context, the return value is `0`. 

 If the HDC is not valid, the return value is `-1`.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd162890%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd162890%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PtVisible">PtVisible Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />