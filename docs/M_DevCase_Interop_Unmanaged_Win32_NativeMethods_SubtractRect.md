# NativeMethods.SubtractRect Method (NativeRectangle, NativeRectangle, NativeRectangle)
 

Determines the coordinates of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> formed by subtracting one <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> from another. 

 The function only subtracts the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> specified by *refSrcRect2* from the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> specified by *refSrcRect1* when the rectangles intersect completely in either the x- or y- direction. 

 For example, if *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 50, 150, 150}, the function sets the coordinates of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refDstRect* to {10, 10, 100, 100}. 

 If *refSrcRect1* has the coordinates {10, 10, 100, 100} and *refSrcRect2* has the coordinates {50, 10, 150, 150}, however, the function sets the coordinates of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refDstRect* to {10, 10, 50, 100}. 

 In other words, the resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> is the bounding box of the geometric difference.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SubtractRect(
	out NativeRectangle refDstRect,
	in NativeRectangle refSrcRect1,
	in NativeRectangle refSrcRect2
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SubtractRect ( 
	<OutAttribute> ByRef refDstRect As NativeRectangle,
	ByRef refSrcRect1 As NativeRectangle,
	ByRef refSrcRect2 As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refDstRect As NativeRectangle
Dim refSrcRect1 As NativeRectangle
Dim refSrcRect2 As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.SubtractRect(refDstRect, 
	refSrcRect1, refSrcRect2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SubtractRect(
	[OutAttribute] NativeRectangle% refDstRect, 
	[InAttribute] NativeRectangle% refSrcRect1, 
	[InAttribute] NativeRectangle% refSrcRect2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SubtractRect : 
        refDstRect : NativeRectangle byref * 
        refSrcRect1 : NativeRectangle byref * 
        refSrcRect2 : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refDstRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that receives the coordinates of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> determined by subtracting the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refSrcRect2* from the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refSrcRect1*.</dd><dt>refSrcRect1</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure from which the function subtracts the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refSrcRect2*.</dd><dt>refSrcRect2</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that the function subtracts from the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> pointed to by *refSrcRect1*.</dd></dl>

#### Return Value
Type: Boolean<br />If the resulting rectangle is empty, the return value is `false` (`False` in Visual Basic). 

 If the resulting rectangle is not empty, the return value is `true` (`True` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145125(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145125(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SubtractRect">SubtractRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />