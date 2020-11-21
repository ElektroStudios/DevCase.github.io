# NativeMethods.ImpersonateSelf Method 
 

Obtains an access token that impersonates the security context of the calling process. The token is assigned to the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ImpersonateSelf(
	SecurityImpersonationLevel impersonationLevel
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ImpersonateSelf ( 
	impersonationLevel As SecurityImpersonationLevel
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim impersonationLevel As SecurityImpersonationLevel
Dim returnValue As Boolean

returnValue = NativeMethods.ImpersonateSelf(impersonationLevel)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
static bool ImpersonateSelf(
	SecurityImpersonationLevel impersonationLevel
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)>]
static member ImpersonateSelf : 
        impersonationLevel : SecurityImpersonationLevel -> bool 

```


#### Parameters
&nbsp;<dl><dt>impersonationLevel</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityImpersonationLevel">DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel</a><br />The impersonation level of the new token.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-impersonateself" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-impersonateself</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />