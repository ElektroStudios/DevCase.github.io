# NativeMethods.RevertToSelf Method 
 

Terminates the impersonation of a client application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
public static bool RevertToSelf()
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function RevertToSelf As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.RevertToSelf()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
static bool RevertToSelf()
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)>]
static member RevertToSelf : unit -> bool 

```


#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-reverttoself" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-reverttoself</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />