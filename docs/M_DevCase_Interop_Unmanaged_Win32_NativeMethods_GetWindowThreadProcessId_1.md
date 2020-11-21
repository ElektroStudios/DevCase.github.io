# NativeMethods.GetWindowThreadProcessId Method (SafeHandle, Int32)
 

Retrieves the identifier of the thread that created the specified window and, optionally, the identifier of the process that created the window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int GetWindowThreadProcessId(
	SafeHandle hWnd,
	out int refPid
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowThreadProcessId ( 
	hWnd As SafeHandle,
	<OutAttribute> ByRef refPid As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refPid As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetWindowThreadProcessId(hWnd, 
	refPid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int GetWindowThreadProcessId(
	SafeHandle^ hWnd, 
	[OutAttribute] int% refPid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowThreadProcessId : 
        hWnd : SafeHandle * 
        refPid : int byref -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the window.</dd><dt>refPid</dt><dd>Type: System.Int32<br />A pointer to a variable that receives the process identifier (PID). 

 If this parameter is not a null reference (`Nothing` in Visual Basic), <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowThreadProcessId">GetWindowThreadProcessId(IntPtr, Int32)</a> copies the identifier of the process to the variable; otherwise, it does not.</dd></dl>

#### Return Value
Type: Int32<br />The identifier of the thread that created the window.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633522%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633522%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowThreadProcessId">GetWindowThreadProcessId Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />