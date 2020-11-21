# NativeMethods.ChildWindowFromPoint Method (IntPtr, NativePoint)
 

Determines which, if any, of the child windows belonging to a parent window contains the specified point. 

 The search is restricted to immediate child windows. Grandchildren, and deeper descendant windows are not searched. 

 To skip certain child windows, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChildWindowFromPointEx">ChildWindowFromPointEx(IntPtr, NativePoint, WindowSkipOptions)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr ChildWindowFromPoint(
	IntPtr hWndParent,
	NativePoint pt
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function ChildWindowFromPoint ( 
	hWndParent As IntPtr,
	pt As NativePoint
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWndParent As IntPtr
Dim pt As NativePoint
Dim returnValue As IntPtr

returnValue = NativeMethods.ChildWindowFromPoint(hWndParent, 
	pt)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr ChildWindowFromPoint(
	IntPtr hWndParent, 
	NativePoint pt
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member ChildWindowFromPoint : 
        hWndParent : IntPtr * 
        pt : NativePoint -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWndParent</dt><dd>Type: System.IntPtr<br />A handle to the parent window.</dd><dt>pt</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A structure that defines the client coordinates, relative to *hWndParent*, of the point to be checked.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is a handle to the child window that contains the point, even if the child window is hidden or disabled. 

 If the point lies outside the parent window, the return value is Zero. 

 If the point is within the parent window but not within any child window, the return value is a handle to the parent window.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-childwindowfrompoint" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-childwindowfrompoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChildWindowFromPoint">ChildWindowFromPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />