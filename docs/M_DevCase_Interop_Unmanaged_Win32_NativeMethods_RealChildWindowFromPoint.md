# NativeMethods.RealChildWindowFromPoint Method (IntPtr, NativePoint)
 

Retrieves a handle to the child window at the specified point. 

 The search is restricted to immediate child windows; grandchildren and deeper descendant windows are not searched.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr RealChildWindowFromPoint(
	IntPtr hwndParent,
	NativePoint pt
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function RealChildWindowFromPoint ( 
	hwndParent As IntPtr,
	pt As NativePoint
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hwndParent As IntPtr
Dim pt As NativePoint
Dim returnValue As IntPtr

returnValue = NativeMethods.RealChildWindowFromPoint(hwndParent, 
	pt)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr RealChildWindowFromPoint(
	IntPtr hwndParent, 
	NativePoint pt
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member RealChildWindowFromPoint : 
        hwndParent : IntPtr * 
        pt : NativePoint -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hwndParent</dt><dd>Type: System.IntPtr<br />A handle to the window whose child is to be retrieved.</dd><dt>pt</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A structure that defines the client coordinates of the point to be checked.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is a handle to the child window that contains the specified point.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-realchildwindowfrompoint" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-realchildwindowfrompoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RealChildWindowFromPoint">RealChildWindowFromPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />