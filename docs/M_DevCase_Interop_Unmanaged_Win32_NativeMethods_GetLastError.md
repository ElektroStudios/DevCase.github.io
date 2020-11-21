# NativeMethods.GetLastError Method 
 

Retrieves the calling thread's last-error code value. 

 The last-error code is maintained on a per-thread basis. Multiple threads do not overwrite each other's last-error code.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static Win32ErrorCode GetLastError()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetLastError As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.GetLastError()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static Win32ErrorCode GetLastError()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetLastError : unit -> Win32ErrorCode 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />The return value is the calling thread's last-error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679360(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679360(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />