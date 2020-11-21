# ProcessLogonFlags Enumeration
 

Specifies how to log on when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithToken">CreateProcessWithToken(IntPtr, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ProcessLogonFlags
```

**VB**<br />
``` VB
Public Enumeration ProcessLogonFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessLogonFlags
```

**C++**<br />
``` C++
public enum class ProcessLogonFlags
```

**F#**<br />
``` F#
type ProcessLogonFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessLogonFlags.NoProfile">**NoProfile**</td><td>0</td><td>Log on without loading the user's profile in the HKEY_USERS registry key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessLogonFlags.UseProfile">**UseProfile**</td><td>1</td><td>Log on, then load the user's profile in the HKEY_USERS registry key. 

 The function returns after the profile has been loaded. 

 Loading the profile can be time-consuming, so it is best to use this value only if you must access the information in the HKEY_CURRENT_USER registry key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessLogonFlags.UseNetCredentialsOnly">**UseNetCredentialsOnly**</td><td>2</td><td>Log on, but use the specified credentials on the network only. 

 The new process uses the same token as the caller, but the system creates a new logon session within LSA, and the process uses the specified credentials as the default credentials. 

 This value can be used To create a process that uses a different set of credentials locally than it does remotely. This is useful in inter-domain scenarios where there is no trust relationship</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createprocesswithtokenw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createprocesswithtokenw</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />