# NativeMethods.ChildWindowFromPointEx Method (IntPtr, Point, WindowSkipOptions)
 

Determines which, if any, of the child windows belonging to the specified parent window contains the specified point. 

 The function can ignore invisible, disabled, and transparent child windows. 

 The search is restricted to immediate child windows. Grandchildren and deeper descendants are not searched.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr ChildWindowFromPointEx(
	IntPtr hwndParent,
	Point pt,
	WindowSkipOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function ChildWindowFromPointEx ( 
	hwndParent As IntPtr,
	pt As Point,
	flags As WindowSkipOptions
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hwndParent As IntPtr
Dim pt As Point
Dim flags As WindowSkipOptions
Dim returnValue As IntPtr

returnValue = NativeMethods.ChildWindowFromPointEx(hwndParent, 
	pt, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr ChildWindowFromPointEx(
	IntPtr hwndParent, 
	Point pt, 
	WindowSkipOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member ChildWindowFromPointEx : 
        hwndParent : IntPtr * 
        pt : Point * 
        flags : WindowSkipOptions -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hwndParent</dt><dd>Type: System.IntPtr<br />A handle to the parent window.</dd><dt>pt</dt><dd>Type: System.Drawing.Point<br />A structure that defines the client coordinates (relative to *hwndParent*) of the point to be checked.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowSkipOptions">DevCase.Interop.Unmanaged.Win32.Enums.WindowSkipOptions</a><br />The child windows to be skipped.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is a handle to the first child window that contains the point and meets the criteria specified by *flags*. 

 If the point is within the parent window but not within any child window that meets the criteria, the return value is a handle to the parent window. 

 If the point lies outside the parent window or if the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-childwindowfrompointex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-childwindowfrompointex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChildWindowFromPointEx">ChildWindowFromPointEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />