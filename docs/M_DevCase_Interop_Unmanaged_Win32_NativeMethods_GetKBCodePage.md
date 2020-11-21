# NativeMethods.GetKBCodePage Method 
 

**Note: This API is now obsolete.**

Retrieves the current code page. 

 Note: This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetOEMCodePage">GetOEMCodePage()</a> function to retrieve the OEM code-page identifier for the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
[ObsoleteAttribute("This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the 'NativeMethods.GetOEMCodePage' function to retrieve the OEM code-page identifier for the system", 
	true)]
public static uint GetKBCodePage()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
<ObsoleteAttribute("This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the 'NativeMethods.GetOEMCodePage' function to retrieve the OEM code-page identifier for the system", 
	true)>
Public Shared Function GetKBCodePage As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetKBCodePage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
[ObsoleteAttribute(L"This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the 'NativeMethods.GetOEMCodePage' function to retrieve the OEM code-page identifier for the system", 
	true)]
static unsigned int GetKBCodePage()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
[<ObsoleteAttribute("This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the 'NativeMethods.GetOEMCodePage' function to retrieve the OEM code-page identifier for the system", 
	true)>]
static member GetKBCodePage : unit -> uint32 

```


#### Return Value
Type: UInt32<br />The return value is an OEM code-page identifier, or it is the default identifier if the registry value is not readable.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getkbcodepage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getkbcodepage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />