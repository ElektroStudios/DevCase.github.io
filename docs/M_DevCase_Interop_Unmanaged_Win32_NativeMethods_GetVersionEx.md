# NativeMethods.GetVersionEx Method 
 

Returns version information about the current operating system. 

 With the release of Windows 8.1, the behavior of the GetVersionEx(OsVersionInfoEx) API has changed in the value it will return for the OS version. The value returned by the GetVersionEx(OsVersionInfoEx) function now depends on how the application is manifested. 

 Applications not manifested for Windows 8.1 or Windows 10 will return the Windows 8 OS version value (6.2). Once an application is manifested for a given operating system version, GetVersionEx(OsVersionInfoEx) will always return the version that the application is manifested for in future releases. 



**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool GetVersionEx(
	ref OsVersionInfoEx refOsVersionInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GetVersionEx ( 
	ByRef refOsVersionInfo As OsVersionInfoEx
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refOsVersionInfo As OsVersionInfoEx
Dim returnValue As Boolean

returnValue = NativeMethods.GetVersionEx(refOsVersionInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool GetVersionEx(
	OsVersionInfoEx% refOsVersionInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GetVersionEx : 
        refOsVersionInfo : OsVersionInfoEx byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refOsVersionInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx">DevCase.Interop.Unmanaged.Win32.Structures.OsVersionInfoEx</a><br />An <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx">OsVersionInfoEx</a> structure that receives the operating system information. 

 Before calling the GetVersionEx(OsVersionInfoEx) function, set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_SizeOfStruct">SizeOfStruct</a> member as appropriate to indicate which data structure is being passed to this function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724451%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724451%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />