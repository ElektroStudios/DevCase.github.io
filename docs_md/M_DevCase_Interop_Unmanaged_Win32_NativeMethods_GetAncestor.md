# NativeMethods.GetAncestor Method (IntPtr, GetAncestorFlags)
 

Retrieves the handle to the ancestor of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr GetAncestor(
	IntPtr hWnd,
	GetAncestorFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetAncestor ( 
	hWnd As IntPtr,
	flags As GetAncestorFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim flags As GetAncestorFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.GetAncestor(hWnd, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr GetAncestor(
	IntPtr hWnd, 
	GetAncestorFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetAncestor : 
        hWnd : IntPtr * 
        flags : GetAncestorFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose ancestor is to be retrieved. 

 If this parameter is the desktop window, the function returns Zero.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetAncestorFlags">DevCase.Interop.Unmanaged.Win32.Enums.GetAncestorFlags</a><br />Flags that determines the ancestor to be retrieved</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the handle to the ancestor window.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633502(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633502(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetAncestor">GetAncestor Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />