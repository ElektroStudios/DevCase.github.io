# NativeMethods.GetWindowPlacement Method (SafeHandle, WindowPlacement)
 

Retrieves the show state and the restored, minimized, and maximized positions of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetWindowPlacement(
	SafeHandle hWnd,
	ref WindowPlacement refWindowPlacement
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowPlacement ( 
	hWnd As SafeHandle,
	ByRef refWindowPlacement As WindowPlacement
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refWindowPlacement As WindowPlacement
Dim returnValue As Boolean

returnValue = NativeMethods.GetWindowPlacement(hWnd, 
	refWindowPlacement)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetWindowPlacement(
	SafeHandle^ hWnd, 
	WindowPlacement% refWindowPlacement
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowPlacement : 
        hWnd : SafeHandle * 
        refWindowPlacement : WindowPlacement byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window.</dd><dt>refWindowPlacement</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement">DevCase.Interop.Unmanaged.Win32.Structures.WindowPlacement</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement">WindowPlacement</a> structure that receives the show state and position information. 

 Before calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowPlacement">GetWindowPlacement(IntPtr, WindowPlacement)</a>, set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_SizeOfStruct">SizeOfStruct</a> member to `Marshal.SizeOf(Of WindowPlacement)`. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowPlacement">GetWindowPlacement(IntPtr, WindowPlacement)</a> fails if *refWindowPlacement* length is not set correctly.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633518%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633518%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowPlacement">GetWindowPlacement Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />