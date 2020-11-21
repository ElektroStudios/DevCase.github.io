# NativeMethods.OffsetRect Method (Rectangle, Int32, Int32)
 

Moves the specified Rectangle by the specified offsets.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool OffsetRect(
	out Rectangle refRect,
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function OffsetRect ( 
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

returnValue = NativeMethods.OffsetRect(refRect, 
	x, y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool OffsetRect(
	[InAttribute] [OutAttribute] Rectangle% refRect, 
	[InAttribute] int x, 
	[InAttribute] int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member OffsetRect : 
        refRect : Rectangle byref * 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure that contains the logical coordinates of the rectangle to be moved.</dd><dt>x</dt><dd>Type: System.Int32<br />Specifies the amount to move the rectangle left or right. 

 This parameter must be a negative value to move the rectangle to the left.</dd><dt>y</dt><dd>Type: System.Int32<br />Specifies the amount to move the rectangle up or down. 

 This parameter must be a negative value to move the rectangle up.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162746(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162746(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_OffsetRect">OffsetRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />