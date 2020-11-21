# NativeMethods.UnionRect Method (NativeRectangle, NativeRectangle, NativeRectangle)
 

Creates the union of two rectangles. The union is the smallest rectangle that contains both source rectangles.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool UnionRect(
	ref NativeRectangle refDstRect,
	ref NativeRectangle refSrcRect1,
	ref NativeRectangle refSrcRect2
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function UnionRect ( 
	ByRef refDstRect As NativeRectangle,
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

returnValue = NativeMethods.UnionRect(refDstRect, 
	refSrcRect1, refSrcRect2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool UnionRect(
	NativeRectangle% refDstRect, 
	NativeRectangle% refSrcRect1, 
	NativeRectangle% refSrcRect2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member UnionRect : 
        refDstRect : NativeRectangle byref * 
        refSrcRect1 : NativeRectangle byref * 
        refSrcRect2 : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refDstRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that will receive a rectangle containing the rectangles pointed to by the *refSrcRect1* and *refSrcRect2* parameters.</dd><dt>refSrcRect1</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that contains the first source rectangle.</dd><dt>refSrcRect2</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that contains the second source rectangle.</dd></dl>

#### Return Value
Type: Boolean<br />If the specified structure contains a nonempty rectangle, the return value is `true` (`True` in Visual Basic). 

 If the specified structure does not contain a nonempty rectangle, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-unionrect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-unionrect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_UnionRect">UnionRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />