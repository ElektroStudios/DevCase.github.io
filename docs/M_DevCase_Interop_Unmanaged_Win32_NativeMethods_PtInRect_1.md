# NativeMethods.PtInRect Method (Rectangle, Point)
 

Determines whether the specified point lies within the specified rectangle. 

 A point is within a rectangle if it lies on the left or top side or is within all four sides. 

 A point on the right or bottom side is considered outside the rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool PtInRect(
	in Rectangle refRect,
	Point pt
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function PtInRect ( 
	ByRef refRect As Rectangle,
	pt As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim pt As Point
Dim returnValue As Boolean

returnValue = NativeMethods.PtInRect(refRect, 
	pt)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool PtInRect(
	[InAttribute] Rectangle% refRect, 
	Point pt
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member PtInRect : 
        refRect : Rectangle byref * 
        pt : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a Rectangle structure that contains the specified rectangle.</dd><dt>pt</dt><dd>Type: System.Drawing.Point<br />A Point structure that contains the specified point.</dd></dl>

#### Return Value
Type: Boolean<br />If the specified point lies within the rectangle, the return value is `true` (`True` in Visual Basic). 

 If the specified point does not lie within the rectangle, the return value is `false` (`False` in Visual Basic)

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162882%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162882%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PtInRect">PtInRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />