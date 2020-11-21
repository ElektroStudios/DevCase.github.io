# NativeMethods.WindowFromPhysicalPoint Method (NativePoint)
 

Retrieves a handle to the window that contains the specified physical point.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr WindowFromPhysicalPoint(
	NativePoint pt
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function WindowFromPhysicalPoint ( 
	pt As NativePoint
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pt As NativePoint
Dim returnValue As IntPtr

returnValue = NativeMethods.WindowFromPhysicalPoint(pt)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr WindowFromPhysicalPoint(
	NativePoint pt
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member WindowFromPhysicalPoint : 
        pt : NativePoint -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pt</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />The physical coordinates of the point</dd></dl>

#### Return Value
Type: IntPtr<br />A handle to the window that contains the given physical point. 

 If no window exists at the point, this value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-windowfromphysicalpoint" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-windowfromphysicalpoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_WindowFromPhysicalPoint">WindowFromPhysicalPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />