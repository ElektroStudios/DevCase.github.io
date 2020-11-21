# NativeMethods.CreateIconIndirect Method 
 

Creates an icon or cursor from an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">IconInfo</a> structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr CreateIconIndirect(
	ref IconInfo refIconinfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CreateIconIndirect ( 
	ByRef refIconinfo As IconInfo
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refIconinfo As IconInfo
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateIconIndirect(refIconinfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr CreateIconIndirect(
	IconInfo% refIconinfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CreateIconIndirect : 
        refIconinfo : IconInfo byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refIconinfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">DevCase.Interop.Unmanaged.Win32.Structures.IconInfo</a><br />\[Missing <param name="refIconinfo"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.CreateIconIndirect(DevCase.Interop.Unmanaged.Win32.Structures.IconInfo@)"\]</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the icon or cursor that is created. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648062(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648062(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />