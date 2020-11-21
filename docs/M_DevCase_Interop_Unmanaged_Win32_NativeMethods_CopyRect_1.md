# NativeMethods.CopyRect Method (Rectangle, Rectangle)
 

Copies the coordinates of one Rectangle to another.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool CopyRect(
	out Rectangle refDstRect,
	in Rectangle refSrcRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function CopyRect ( 
	<OutAttribute> ByRef refDstRect As Rectangle,
	ByRef refSrcRect As Rectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refDstRect As Rectangle
Dim refSrcRect As Rectangle
Dim returnValue As Boolean

returnValue = NativeMethods.CopyRect(refDstRect, 
	refSrcRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool CopyRect(
	[OutAttribute] Rectangle% refDstRect, 
	[InAttribute] Rectangle% refSrcRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member CopyRect : 
        refDstRect : Rectangle byref * 
        refSrcRect : Rectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refDstRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure that receives the logical coordinates of the source rectangle.</dd><dt>refSrcRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure whose coordinates are to be copied in logical units.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183481(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183481(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CopyRect">CopyRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />