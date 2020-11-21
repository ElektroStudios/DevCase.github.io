# NativeMethods.GetParent Method (SafeHandle)
 

Retrieves a handle to the specified window's parent or owner. 

 To retrieve a handle to a specified ancestor, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetAncestor">GetAncestor(IntPtr, GetAncestorFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr GetParent(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetParent ( 
	hWnd As SafeHandle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As IntPtr

returnValue = NativeMethods.GetParent(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr GetParent(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetParent : 
        hWnd : SafeHandle -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose parent window handle is to be retrieved.</dd></dl>

#### Return Value
Type: IntPtr<br />If the window is a child window, the return value is a handle to the parent window. 

 If the window is a top-level window with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStyles">Popup</a> style, the return value is a handle to the owner window. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633510(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633510(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetParent">GetParent Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />