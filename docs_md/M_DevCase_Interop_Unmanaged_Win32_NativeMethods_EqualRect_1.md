# NativeMethods.EqualRect Method (Rectangle, Rectangle)
 

Determines whether the two specified <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> are equal by comparing the coordinates of their upper-left and lower-right corners. 

 Note that the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EqualRect">EqualRect(NativeRectangle, NativeRectangle)</a> function does not treat empty rectangles as equal if their coordinates are different.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool EqualRect(
	in Rectangle refRect1,
	in Rectangle refRect2
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function EqualRect ( 
	ByRef refRect1 As Rectangle,
	ByRef refRect2 As Rectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refRect1 As Rectangle
Dim refRect2 As Rectangle
Dim returnValue As Boolean

returnValue = NativeMethods.EqualRect(refRect1, 
	refRect2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool EqualRect(
	[InAttribute] Rectangle% refRect1, 
	[InAttribute] Rectangle% refRect2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member EqualRect : 
        refRect1 : Rectangle byref * 
        refRect2 : Rectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect1</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the logical coordinates of the first rectangle.</dd><dt>refRect2</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the logical coordinates of the second rectangle.</dd></dl>

#### Return Value
Type: Boolean<br />If the two rectangles are identical, the return value is `true` (`True` in Visual Basic). 

 If the two rectangles are not identical, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162699(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162699(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EqualRect">EqualRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />