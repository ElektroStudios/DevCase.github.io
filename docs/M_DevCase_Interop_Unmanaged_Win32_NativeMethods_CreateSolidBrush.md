# NativeMethods.CreateSolidBrush Method 
 

Creates a logical brush that has the specified solid color. 

 A solid brush is a bitmap that the system uses to paint the interiors of filled shapes. 

 After an application creates a brush by calling CreateSolidBrush(UInt32), it can select that brush into any device context by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SelectObject">SelectObject(IntPtr, IntPtr)</a> function. 

 When you no longer need the brush, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteObject">DeleteObject(IntPtr)</a> function to delete it.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll")]
public static IntPtr CreateSolidBrush(
	uint color
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll">]
Public Shared Function CreateSolidBrush ( 
	color As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim color As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateSolidBrush(color)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll")]
static IntPtr CreateSolidBrush(
	unsigned int color
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll")>]
static member CreateSolidBrush : 
        color : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.UInt32<br />The color of the brush. 

 To create a `COLORREF` color value, use the `RGB` macro.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value identifies a logical brush. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183518%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183518%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />