# NativeMethods.GetSystemMenu Method (IntPtr, Boolean)
 

Gets the handle of the form's system menu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static IntPtr GetSystemMenu(
	IntPtr hWnd,
	bool bRevert
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetSystemMenu ( 
	hWnd As IntPtr,
	bRevert As Boolean
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim bRevert As Boolean
Dim returnValue As IntPtr

returnValue = NativeMethods.GetSystemMenu(hWnd, 
	bRevert)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static IntPtr GetSystemMenu(
	IntPtr hWnd, 
	bool bRevert
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetSystemMenu : 
        hWnd : IntPtr * 
        bRevert : bool -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The handle of the form for which to get the system menu.</dd><dt>bRevert</dt><dd>Type: System.Boolean<br />Indicates whether the menu should be reset to its original state.</dd></dl>

#### Return Value
Type: IntPtr<br />The handle of the system menu of the specified form.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647985%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647985%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetSystemMenu">GetSystemMenu Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />