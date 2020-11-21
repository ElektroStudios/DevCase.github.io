# SecurityImpersonationLevel Enumeration
 

Specifies security impersonation levels. 

 Security impersonation levels govern the degree to which a server process can act on behalf of a client process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum SecurityImpersonationLevel
```

**VB**<br />
``` VB
Public Enumeration SecurityImpersonationLevel
```

**VB Usage**<br />
``` VB Usage
Dim instance As SecurityImpersonationLevel
```

**C++**<br />
``` C++
public enum class SecurityImpersonationLevel
```

**F#**<br />
``` F#
type SecurityImpersonationLevel
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel.SecurityAnonymous">**SecurityAnonymous**</td><td>0</td><td>The server process cannot obtain identification information about the client, and it cannot impersonate the client. 

 It is defined with no value given, and thus, by `ANSI C` rules, defaults to a value of `0`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel.SecurityIdentification">**SecurityIdentification**</td><td>1</td><td>The server process can obtain information about the client, such as security identifiers and privileges, but it cannot impersonate the client. 

 This is useful for servers that export their own objects, for example, database products that export tables and views. 

 Using the retrieved client-security information, the server can make access-validation decisions without being able to use other services that are using the client's security context.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel.SecurityImpersonation">**SecurityImpersonation**</td><td>2</td><td>The server process can impersonate the client's security context on its local system. 

 The server cannot impersonate the client on remote systems.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel.SecurityDelegation">**SecurityDelegation**</td><td>3</td><td>The server process can impersonate the client's security context on remote systems.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379572(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379572(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />