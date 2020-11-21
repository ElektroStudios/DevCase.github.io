# NativeMethods.GetDC Method (SafeHandle)
 

Retrieves a IntPtr handle to a device context (DC) for the client area of a specified window or for the entire screen. 

 You can use the returned handle in subsequent GDI functions to draw in the DC. 

 The device context is an opaque data structure, whose values are used internally by GDI.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static IntPtr GetDC(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetDC ( 
	hWnd As SafeHandle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As IntPtr

returnValue = NativeMethods.GetDC(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static IntPtr GetDC(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetDC : 
        hWnd : SafeHandle -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the window whose DC is to be retrieved. 

 If this value is Zero, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDC">GetDC(IntPtr)</a> retrieves the DC for the entire screen.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a IntPtr handle to the DC for the specified window's client area. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144871%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144871%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDC">GetDC Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />