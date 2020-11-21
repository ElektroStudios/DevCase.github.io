# NativeMethods.GetWindowInfo Method (IntPtr, NativeWindowInfo)
 

Retrieves information about the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetWindowInfo(
	IntPtr hWnd,
	ref NativeWindowInfo refWindowInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowInfo ( 
	hWnd As IntPtr,
	ByRef refWindowInfo As NativeWindowInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refWindowInfo As NativeWindowInfo
Dim returnValue As Boolean

returnValue = NativeMethods.GetWindowInfo(hWnd, 
	refWindowInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetWindowInfo(
	IntPtr hWnd, 
	NativeWindowInfo% refWindowInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowInfo : 
        hWnd : IntPtr * 
        refWindowInfo : NativeWindowInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose information is to be retrieved.</dd><dt>refWindowInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeWindowInfo">DevCase.Interop.Unmanaged.Win32.Structures.NativeWindowInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeWindowInfo">NativeWindowInfo</a> structure to receive the information. 

 Note that you must set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeWindowInfo_SizeOfStruct">SizeOfStruct</a> member to `Marshal.SizeOf(Of NativeWindowInfo)` before calling this function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633516%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633516%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowInfo">GetWindowInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />