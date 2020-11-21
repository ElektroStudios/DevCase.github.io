# NativeMethods.SubtractRect Method (Rectangle, Rectangle, Rectangle)
 

Determines the coordinates of a Rectangle formed by subtracting one Rectangle from another. 

 The function only subtracts the Rectangle specified by *refSrcRect2* from the Rectangle specified by *refSrcRect1* when the rectangles intersect completely in either the x- or y- direction. 

 For example, if *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 50, 150, 150}, the function sets the coordinates of the Rectangle pointed to by *refDstRect* to {10, 10, 100, 100}. 

 If *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 10, 150, 150}, however, the function sets the coordinates of the Rectangle pointed to by *refDstRect* to {10, 10, 50, 100}. 

 In other words, the resulting Rectangle is the bounding box of the geometric difference.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SubtractRect(
	out Rectangle refDstRect,
	in Rectangle refSrcRect1,
	in Rectangle refSrcRect2
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SubtractRect ( 
	<OutAttribute> ByRef refDstRect As Rectangle,
	ByRef refSrcRect1 As Rectangle,
	ByRef refSrcRect2 As Rectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refDstRect As Rectangle
Dim refSrcRect1 As Rectangle
Dim refSrcRect2 As Rectangle
Dim returnValue As Boolean

returnValue = NativeMethods.SubtractRect(refDstRect, 
	refSrcRect1, refSrcRect2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SubtractRect(
	[OutAttribute] Rectangle% refDstRect, 
	[InAttribute] Rectangle% refSrcRect1, 
	[InAttribute] Rectangle% refSrcRect2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SubtractRect : 
        refDstRect : Rectangle byref * 
        refSrcRect1 : Rectangle byref * 
        refSrcRect2 : Rectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refDstRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure that receives the coordinates of the Rectangle determined by subtracting the Rectangle pointed to by *refSrcRect2* from the Rectangle pointed to by *refSrcRect1*.</dd><dt>refSrcRect1</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a Rectangle structure from which the function subtracts the Rectangle pointed to by *refSrcRect2*.</dd><dt>refSrcRect2</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a Rectangle structure that the function subtracts from the Rectangle pointed to by *refSrcRect1*.</dd></dl>

#### Return Value
Type: Boolean<br />If the resulting rectangle is empty, the return value is `false` (`False` in Visual Basic). 

 If the resulting rectangle is not empty, the return value is `true` (`True` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145125(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145125(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SubtractRect">SubtractRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />