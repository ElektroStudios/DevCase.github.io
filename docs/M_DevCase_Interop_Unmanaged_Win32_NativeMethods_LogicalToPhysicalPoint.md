# NativeMethods.LogicalToPhysicalPoint Method 
 

Converts the logical coordinates of a point in a window to physical coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool LogicalToPhysicalPoint(
	IntPtr hWnd,
	ref Point refPoint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function LogicalToPhysicalPoint ( 
	hWnd As IntPtr,
	ByRef refPoint As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refPoint As Point
Dim returnValue As Boolean

returnValue = NativeMethods.LogicalToPhysicalPoint(hWnd, 
	refPoint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool LogicalToPhysicalPoint(
	IntPtr hWnd, 
	Point% refPoint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member LogicalToPhysicalPoint : 
        hWnd : IntPtr * 
        refPoint : Point byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose transform is used for the conversion. 

 Top level windows are fully supported. In the case of child windows, only the area of overlap between the parent and the child window is converted.</dd><dt>refPoint</dt><dd>Type: System.Drawing.Point<br />A structure that specifies the logical coordinates to be converted. 

 The new physical coordinates are copied into this structure if the function succeeds.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-logicaltophysicalpoint" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-logicaltophysicalpoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />