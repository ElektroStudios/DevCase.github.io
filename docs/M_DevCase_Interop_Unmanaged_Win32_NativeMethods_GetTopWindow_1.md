# NativeMethods.GetTopWindow Method (SafeHandle)
 

Examines the Z order of the child windows associated with the specified parent window and retrieves a handle to the child window at the top of the Z order.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GetTopWindow(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetTopWindow ( 
	hWnd As SafeHandle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As IntPtr

returnValue = NativeMethods.GetTopWindow(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GetTopWindow(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetTopWindow : 
        hWnd : SafeHandle -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the parent window whose child windows are to be examined. 

 If this parameter is Zero, the function returns a handle to the window at the top of the Z order.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the child window at the top of the Z order. 

 If the specified window has no child windows, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633514%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633514%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetTopWindow">GetTopWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />