# RegNotifyChangeFilter Enumeration
 

Specifies the changes that should be reported when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegNotifyChangeKeyValue">RegNotifyChangeKeyValue(SafeRegistryHandle, Boolean, RegNotifyChangeFilter, IntPtr, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum RegNotifyChangeFilter
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration RegNotifyChangeFilter
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegNotifyChangeFilter
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class RegNotifyChangeFilter
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type RegNotifyChangeFilter
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegNotifyChangeFilter.Key">**Key**</td><td>1</td><td>Notify the caller if a subkey Is added Or deleted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegNotifyChangeFilter.Attribute">**Attribute**</td><td>2</td><td>Notify the caller of changes to the attributes of the key, such as the security descriptor information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegNotifyChangeFilter.Value">**Value**</td><td>4</td><td>Notify the caller of changes to a value of the key. 

 This can include adding or deleting a value, or changing an existing value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegNotifyChangeFilter.Security">**Security**</td><td>8</td><td>Notify the caller of changes to the security descriptor of the key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegNotifyChangeFilter.Agnostic">**Agnostic**</td><td>268435456</td><td>Indicates that the lifetime of the registration must not be tied to the lifetime of the thread issuing the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegNotifyChangeKeyValue">RegNotifyChangeKeyValue(SafeRegistryHandle, Boolean, RegNotifyChangeFilter, IntPtr, Boolean)</a> call.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regnotifychangekeyvalue" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regnotifychangekeyvalue</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />