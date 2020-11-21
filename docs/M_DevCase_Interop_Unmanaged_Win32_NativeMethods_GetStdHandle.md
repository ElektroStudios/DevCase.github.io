# NativeMethods.GetStdHandle Method 
 

Retrieves a handle to the specified standard device (standard input, standard output, or standard error).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr GetStdHandle(
	StandardDevice std
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GetStdHandle ( 
	std As StandardDevice
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim std As StandardDevice
Dim returnValue As IntPtr

returnValue = NativeMethods.GetStdHandle(std)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr GetStdHandle(
	StandardDevice std
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GetStdHandle : 
        std : StandardDevice -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>std</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardDevice">DevCase.Interop.Unmanaged.Win32.Enums.StandardDevice</a><br />A handle to the standard device.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the specified device, or a redirected handle set by a previous call to SetStdHandle. 

 The handle has `GENERIC_READ` and `GENERIC_WRITE` access rights, unless the application has used SetStdHandle to set a standard handle with lesser access. 

 If the function fails, the return value is `INVALID_HANDLE_VALUE` ( `New IntPtr(-1)` ). 

 To get extended error information, call GetLastWin32Error(). 

 If an application does not have associated standard handles, such as a service running on an interactive desktop, and has not redirected them, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getstdhandle" target="_blank">https://docs.microsoft.com/en-us/windows/console/getstdhandle</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />