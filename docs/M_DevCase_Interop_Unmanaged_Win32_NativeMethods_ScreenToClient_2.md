# NativeMethods.ScreenToClient Method (SafeHandle, NativePoint)
 

Converts the screen coordinates of a specified point on the screen to client-area coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool ScreenToClient(
	SafeHandle hWnd,
	ref NativePoint refPoint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function ScreenToClient ( 
	hWnd As SafeHandle,
	ByRef refPoint As NativePoint
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refPoint As NativePoint
Dim returnValue As Boolean

returnValue = NativeMethods.ScreenToClient(hWnd, 
	refPoint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool ScreenToClient(
	SafeHandle^ hWnd, 
	NativePoint% refPoint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member ScreenToClient : 
        hWnd : SafeHandle * 
        refPoint : NativePoint byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle To the window whose client area will be used For the conversion.</dd><dt>refPoint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structure that specifies the screen coordinates to be converted. 

 The new screen coordinates are copied into this structure if the function succeeds.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162952%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162952%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ScreenToClient">ScreenToClient Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />