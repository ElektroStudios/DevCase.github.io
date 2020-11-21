# NativeMethods.GetUpdateRect Method (IntPtr, NativeRectangle, Boolean)
 

Retrieves the coordinates of the smallest rectangle that completely encloses the update region of the specified window. 

GetUpdateRect(IntPtr, NativeRectangle, Boolean) retrieves the rectangle in logical coordinates. If there is no update region, GetUpdateRect(IntPtr, NativeRectangle, Boolean) retrieves an empty rectangle (sets all coordinates to zero).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetUpdateRect(
	IntPtr hWnd,
	ref NativeRectangle refRect,
	bool erase
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetUpdateRect ( 
	hWnd As IntPtr,
	ByRef refRect As NativeRectangle,
	erase As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refRect As NativeRectangle
Dim erase As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.GetUpdateRect(hWnd, 
	refRect, erase)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetUpdateRect(
	IntPtr hWnd, 
	NativeRectangle% refRect, 
	bool erase
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetUpdateRect : 
        hWnd : IntPtr * 
        refRect : NativeRectangle byref * 
        erase : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose update region is to be retrieved.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that receives the coordinates, in device units, of the enclosing rectangle. 

 An application can set this parameter to a null reference (`Nothing` in Visual Basic) to determine whether an update region exists for the window. 

 If this parameter is a null reference (`Nothing` in Visual Basic), GetUpdateRect(IntPtr, NativeRectangle, Boolean) returns nonzero if an update region exists, and zero if one does not. This provides a simple and efficient means of determining whether a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message resulted from an invalid area.</dd><dt>erase</dt><dd>Type: System.Boolean<br />\[Missing <param name="erase"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.GetUpdateRect(System.IntPtr,DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle@,System.Boolean)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the update region is not empty, the return value is `true` (`True` in Visual Basic). 

 If there is no update region, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getupdaterect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getupdaterect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetUpdateRect">GetUpdateRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />