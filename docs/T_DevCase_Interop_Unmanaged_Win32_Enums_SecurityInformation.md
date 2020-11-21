# SecurityInformation Enumeration
 

Specifies the object-related security information being set or queried.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SecurityInformation
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SecurityInformation
```

**VB Usage**<br />
``` VB Usage
Dim instance As SecurityInformation
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SecurityInformation
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SecurityInformation
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.Owner">**Owner**</td><td>1</td><td>The owner identifier of the object is being referenced.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.Group">**Group**</td><td>2</td><td>The primary group identifier of the object is being referenced.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.DACL">**DACL**</td><td>4</td><td>The DACL of the object is being referenced.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.SACL">**SACL**</td><td>8</td><td>The SACL of the object is being referenced.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.ProtectedDACL">**ProtectedDACL**</td><td>2147483648</td><td>The DACL cannot inherit access control entries (ACEs).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.ProtectedSACL">**ProtectedSACL**</td><td>1073741824</td><td>The SACL cannot inherit ACEs.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.UnprotectedDACL">**UnprotectedDACL**</td><td>536870912</td><td>The DACL inherits ACEs from the parent object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation.UnprotectedSACL">**UnprotectedSACL**</td><td>268435456</td><td>The SACL inherits ACEs from the parent object.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379573(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379573(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />