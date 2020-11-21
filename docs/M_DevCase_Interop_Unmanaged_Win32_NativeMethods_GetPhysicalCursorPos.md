# NativeMethods.GetPhysicalCursorPos Method 
 

Retrieves the position of the cursor in physical coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool GetPhysicalCursorPos(
	ref NativePoint refPoint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetPhysicalCursorPos ( 
	ByRef refPoint As NativePoint
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refPoint As NativePoint
Dim returnValue As Boolean

returnValue = NativeMethods.GetPhysicalCursorPos(refPoint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool GetPhysicalCursorPos(
	NativePoint% refPoint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetPhysicalCursorPos : 
        refPoint : NativePoint byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refPoint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structure that receives the physical coordinates of the cursor.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful or `false` (`False` in Visual Basic) otherwise. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getphysicalcursorpos" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getphysicalcursorpos</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />