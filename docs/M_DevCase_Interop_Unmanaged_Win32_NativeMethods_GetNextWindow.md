# NativeMethods.GetNextWindow Method (IntPtr, GetNextWindowCmd)
 

Retrieves a handle to the next or previous window in the Z-Order. 

 The next window is below the specified window; the previous window is above. 

 If the specified window is a topmost window, the function searches for a topmost window. 

 If the specified window is a top-level window, the function searches for a top-level window. 

 If the specified window is a child window, the function searches for a child window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", EntryPoint = "GetWindow", SetLastError = true)]
public static IntPtr GetNextWindow(
	IntPtr hWnd,
	GetNextWindowCmd cmd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", EntryPoint := "GetWindow", SetLastError := true>]
Public Shared Function GetNextWindow ( 
	hWnd As IntPtr,
	cmd As GetNextWindowCmd
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim cmd As GetNextWindowCmd
Dim returnValue As IntPtr

returnValue = NativeMethods.GetNextWindow(hWnd, 
	cmd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", EntryPoint = L"GetWindow", SetLastError = true)]
static IntPtr GetNextWindow(
	IntPtr hWnd, 
	GetNextWindowCmd cmd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", EntryPoint = "GetWindow", SetLastError = true)>]
static member GetNextWindow : 
        hWnd : IntPtr * 
        cmd : GetNextWindowCmd -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to a window. The window handle retrieved is relative to this window, based on the value of the wCmd parameter.</dd><dt>cmd</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetNextWindowCmd">DevCase.Interop.Unmanaged.Win32.Enums.GetNextWindowCmd</a><br />Indicates whether the function returns a handle to the next window, or the previous window.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the next (or previous) window. 

 If there is no next (or previous) window, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633509%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633509%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetNextWindow">GetNextWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />