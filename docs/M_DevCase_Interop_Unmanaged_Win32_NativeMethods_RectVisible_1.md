# NativeMethods.RectVisible Method (IntPtr, Rectangle)
 

Determines whether any part of the specified rectangle lies within the clipping region of a device context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static int RectVisible(
	IntPtr hdc,
	in Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function RectVisible ( 
	hdc As IntPtr,
	ByRef refRect As Rectangle
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim refRect As Rectangle
Dim returnValue As Integer

returnValue = NativeMethods.RectVisible(hdc, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static int RectVisible(
	IntPtr hdc, 
	[InAttribute] Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member RectVisible : 
        hdc : IntPtr * 
        refRect : Rectangle byref -> int 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle to the device context (DC).</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a Rectangle structure that contains the logical coordinates of the specified rectangle.</dd></dl>

#### Return Value
Type: Int32<br />If the current transform does not have a rotation and the rectangle lies within the clipping region, the return value is `1`. 

 If the current transform does not have a rotation and the rectangle does not lie within the clipping region, the return value is `0`. 

 If the current transform has a rotation and the rectangle lies within the clipping region, the return value is `2`. 

 If the current transform has a rotation and the rectangle does not lie within the clipping region, the return value is `1`.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd162908%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd162908%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RectVisible">RectVisible Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />