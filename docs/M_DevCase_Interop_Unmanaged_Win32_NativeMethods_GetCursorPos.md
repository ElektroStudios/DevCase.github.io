# NativeMethods.GetCursorPos Method (NativePoint)
 

Retrieves the position of the mouse cursor, in screen coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool GetCursorPos(
	ref NativePoint refPoint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetCursorPos ( 
	ByRef refPoint As NativePoint
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refPoint As NativePoint
Dim returnValue As Boolean

returnValue = NativeMethods.GetCursorPos(refPoint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool GetCursorPos(
	NativePoint% refPoint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetCursorPos : 
        refPoint : NativePoint byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refPoint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structure that receives the screen coordinates of the cursor.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful or `false` (`False` in Visual Basic) otherwise. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648390%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648390%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCursorPos">GetCursorPos Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />