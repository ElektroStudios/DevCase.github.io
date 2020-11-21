# NativeMethods.WindowFromPoint Method (NativePoint)
 

Retrieves a handle to the window that contains the specified point.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr WindowFromPoint(
	NativePoint pt
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function WindowFromPoint ( 
	pt As NativePoint
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pt As NativePoint
Dim returnValue As IntPtr

returnValue = NativeMethods.WindowFromPoint(pt)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr WindowFromPoint(
	NativePoint pt
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member WindowFromPoint : 
        pt : NativePoint -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pt</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />The point to be checked.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is a handle to the window that contains the point. 

 If no window exists at the given point, the return value is Zero. 

 If the point is over a static text control, the return value is a handle to the window under the static text control.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633558%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633558%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_WindowFromPoint">WindowFromPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />