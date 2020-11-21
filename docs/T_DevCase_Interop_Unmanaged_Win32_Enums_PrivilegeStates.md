# PrivilegeStates Enumeration
 

Specifies a privilege state.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PrivilegeStates
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PrivilegeStates
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrivilegeStates
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PrivilegeStates
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PrivilegeStates
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates.PrivilegeDisabled">**PrivilegeDisabled**</td><td>0</td><td>The privilege is disabled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates.PrivilegeEnabledByDefault">**PrivilegeEnabledByDefault**</td><td>1</td><td>The privilege is enabled by default.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates.PrivilegeEnabled">**PrivilegeEnabled**</td><td>2</td><td>The privilege is enabled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates.PrivilegeRemoved">**PrivilegeRemoved**</td><td>4</td><td>Used to remove a privilege.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates.PrivilegeUsedForAccess">**PrivilegeUsedForAccess**</td><td>2147483648</td><td>The privilege was used to gain access to an object or service. 

 This flag is used to identify the relevant privileges in a set passed by a client application that may contain unnecessary privileges</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379630%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379630%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />