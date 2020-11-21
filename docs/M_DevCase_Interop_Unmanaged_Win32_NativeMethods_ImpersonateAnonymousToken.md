# NativeMethods.ImpersonateAnonymousToken Method 
 

Enables the specified thread to impersonate the system's anonymous logon token. 

 To ensure that a token matches the operating system's concept of anonymous access, this function should be called before attempting network access to generate an anonymous token on the remote server.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ImpersonateAnonymousToken(
	IntPtr hThread
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ImpersonateAnonymousToken ( 
	hThread As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ImpersonateAnonymousToken(hThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
static bool ImpersonateAnonymousToken(
	IntPtr hThread
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)>]
static member ImpersonateAnonymousToken : 
        hThread : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the thread to impersonate the system's anonymous logon token.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-impersonateanonymoustoken" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-impersonateanonymoustoken</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />