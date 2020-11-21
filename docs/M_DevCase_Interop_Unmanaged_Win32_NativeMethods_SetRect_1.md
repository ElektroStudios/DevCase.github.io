# NativeMethods.SetRect Method (Rectangle, Int32, Int32, Int32, Int32)
 

Sets the coordinates of the specified rectangle. 

 This is equivalent to assigning the left, top, right, and bottom arguments to the appropriate members of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SetRect(
	out Rectangle refRect,
	int xLeft,
	int yTop,
	int xRight,
	int yBottom
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SetRect ( 
	<OutAttribute> ByRef refRect As Rectangle,
	xLeft As Integer,
	yTop As Integer,
	xRight As Integer,
	yBottom As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim xLeft As Integer
Dim yTop As Integer
Dim xRight As Integer
Dim yBottom As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.SetRect(refRect, 
	xLeft, yTop, xRight, yBottom)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SetRect(
	[OutAttribute] Rectangle% refRect, 
	int xLeft, 
	int yTop, 
	int xRight, 
	int yBottom
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SetRect : 
        refRect : Rectangle byref * 
        xLeft : int * 
        yTop : int * 
        xRight : int * 
        yBottom : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure that contains the rectangle to be set.</dd><dt>xLeft</dt><dd>Type: System.Int32<br />Specifies the x-coordinate of the rectangle's upper-left corner.</dd><dt>yTop</dt><dd>Type: System.Int32<br />Specifies the y-coordinate of the rectangle's upper-left corner.</dd><dt>xRight</dt><dd>Type: System.Int32<br />Specifies the x-coordinate of the rectangle's lower-right corner.</dd><dt>yBottom</dt><dd>Type: System.Int32<br />Specifies the y-coordinate of the rectangle's lower-right corner.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145085(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145085(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetRect">SetRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />