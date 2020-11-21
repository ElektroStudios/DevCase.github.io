# StandardAccessRights Enumeration
 

Specifies the access rights that correspond to operations specific to a standard object type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum StandardAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration StandardAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As StandardAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class StandardAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type StandardAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.Delete">**Delete**</td><td>65536</td><td>The right to delete the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.ReadControl">**ReadControl**</td><td>131072</td><td>The right to read the information in the object's security descriptor, not including the information in the system access control list (SACL).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.WriteDac">**WriteDac**</td><td>262144</td><td>The right to modify the discretionary access control list (DACL) in the object's security descriptor.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.WriteOwner">**WriteOwner**</td><td>524288</td><td>The right to change the owner in the object's security descriptor.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.Synchronize">**Synchronize**</td><td>1048576</td><td>The right to use the object for synchronization. 

 This enables a thread to wait until the object is in the signaled state. 

 Some object types do not support this access right.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.StandardRightsRequired">**StandardRightsRequired**</td><td>983040</td><td>Combines Delete, ReadControl, WriteDac, and WriteOwner access.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.StandardRightsRead">**StandardRightsRead**</td><td>131072</td><td>Same as ReadControl.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.StandardRightsWrite">**StandardRightsWrite**</td><td>131072</td><td>Same as ReadControl.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.StandardRightsExecute">**StandardRightsExecute**</td><td>131072</td><td>Same as ReadControl.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights.StandardRightsAll">**StandardRightsAll**</td><td>2031616</td><td>Combines Delete, ReadControl, WriteDac, WriteOwner, and Synchronize access.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379607(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379607(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />