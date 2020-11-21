# TokenAccess Enumeration
 

Flags combination for `desiredAccess` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenProcessToken">OpenProcessToken(SafeProcessHandle, TokenAccess, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum TokenAccess
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration TokenAccess
```

**VB Usage**<br />
``` VB Usage
Dim instance As TokenAccess
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class TokenAccess
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type TokenAccess
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.StandardRightsRequired">**StandardRightsRequired**</td><td>983040</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.StandradRightsRead">**StandradRightsRead**</td><td>131072</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.AssignPrimary">**AssignPrimary**</td><td>1</td><td>Required to attach a primary token to a process. 

 The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">AssignPrimaryTokenPrivilege</a> privilege is also required to accomplish this task.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.Duplicate">**Duplicate**</td><td>2</td><td>Required to duplicate an access token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.Impersonate">**Impersonate**</td><td>4</td><td>Required to attach an impersonation access token to a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.Query">**Query**</td><td>8</td><td>Required to query an access token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.QuerySource">**QuerySource**</td><td>16</td><td>Required to query the source of an access token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.AdjustPrivileges">**AdjustPrivileges**</td><td>32</td><td>Required to enable or disable the privileges in an access token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.AdjustGroups">**AdjustGroups**</td><td>64</td><td>Required to adjust the attributes of the groups in an access token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.AdjustDefault">**AdjustDefault**</td><td>128</td><td>Required to change the default owner, primary group, or `DACL` of an access token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.AdjustSessionId">**AdjustSessionId**</td><td>256</td><td>Required to adjust the session ID of an access token. 

 The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">TcbPrivilege</a> privilege is required.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.Read">**Read**</td><td>983048</td><td>Combines StandardRightsRequired and Query.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess.AllAccess">**AllAccess**</td><td>983551</td><td>Combines all possible access rights for a token.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />