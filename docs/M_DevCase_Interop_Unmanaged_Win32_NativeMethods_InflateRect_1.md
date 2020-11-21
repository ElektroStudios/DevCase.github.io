# NativeMethods.InflateRect Method (Rectangle, Int32, Int32)
 

Increases or decreases the width and height of the specified <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InflateRect">InflateRect(NativeRectangle, Int32, Int32)</a> function adds 'x' units to the left and right ends of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> and 'y' units to the top and bottom. 

 The *x* and *y* parameters are signed values; positive values increase the width and height, and negative values decrease them.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool InflateRect(
	out Rectangle refRect,
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function InflateRect ( 
	<OutAttribute> ByRef refRect As Rectangle,
	x As Integer,
	y As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim x As Integer
Dim y As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.InflateRect(refRect, 
	x, y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool InflateRect(
	[InAttribute] [OutAttribute] Rectangle% refRect, 
	[InAttribute] int x, 
	[InAttribute] int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member InflateRect : 
        refRect : Rectangle byref * 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure to be increased or decreased.</dd><dt>x</dt><dd>Type: System.Int32<br />The amount to increase or decrease the Rectangle width. 

 This parameter must be negative to decrease the width.</dd><dt>y</dt><dd>Type: System.Int32<br />The amount to increase or decrease the Rectangle height. 

 This parameter must be negative to decrease the height.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144994(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144994(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_InflateRect">InflateRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />