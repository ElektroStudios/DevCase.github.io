# NativeMethods.RegCloseKey Method (IntPtr)
 

Closes a handle to the specified registry key.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static Win32ErrorCode RegCloseKey(
	IntPtr hKey
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function RegCloseKey ( 
	hKey As IntPtr
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim hKey As IntPtr
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.RegCloseKey(hKey)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static Win32ErrorCode RegCloseKey(
	IntPtr hKey
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member RegCloseKey : 
        hKey : IntPtr -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>hKey</dt><dd>Type: System.IntPtr<br />A handle to the open key to be closed. 

 The handle must have been opened by the RegCreateKeyEx, RegCreateKeyTransacted, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegOpenKeyEx">RegOpenKeyEx(SafeRegistryHandle, String, UInt32, Int32, IntPtr)</a>, RegOpenKeyTransacted, or RegConnectRegistry function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regclosekey" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regclosekey</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegCloseKey">RegCloseKey Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />