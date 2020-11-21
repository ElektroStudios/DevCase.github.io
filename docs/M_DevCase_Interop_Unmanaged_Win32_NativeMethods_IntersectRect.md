# NativeMethods.IntersectRect Method 
 

Calculates the intersection of two source <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> and places the coordinates of the intersection <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> into the destination <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>. 

 If the source <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> do not intersect, an empty <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> (in which all coordinates are set to zero) is placed into the destination <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool IntersectRect(
	out NativeRectangle refDstRect,
	in NativeRectangle refSrcRect1,
	in NativeRectangle refSrcRect2
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function IntersectRect ( 
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

returnValue = NativeMethods.IntersectRect(refDstRect, 
	refSrcRect1, refSrcRect2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool IntersectRect(
	[OutAttribute] NativeRectangle% refDstRect, 
	[InAttribute] NativeRectangle% refSrcRect1, 
	[InAttribute] NativeRectangle% refSrcRect2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member IntersectRect : 
        refDstRect : NativeRectangle byref * 
        refSrcRect1 : NativeRectangle byref * 
        refSrcRect2 : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refDstRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that is to receive the intersection of the rectangles pointed to by the *refSrcRect1* and *refSrcRect2* parameters. 

 This parameter cannot be a null reference (`Nothing` in Visual Basic).</dd><dt>refSrcRect1</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the first source rectangle.</dd><dt>refSrcRect2</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the second source rectangle.</dd></dl>

#### Return Value
Type: Boolean<br />If the rectangles intersect, the return value is `true` (`True` in Visual Basic). 

 If the rectangles do not intersect, the return value is `false` (`False` in Visual Basic)

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145001%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145001%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />