# EnumProcessModulesFilter Enumeration
 

Filter for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumProcessModulesEx">EnumProcessModulesEx(IntPtr, IntPtr[], UInt32, UInt32, EnumProcessModulesFilter)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum EnumProcessModulesFilter
```

**VB**<br />
``` VB
Public Enumeration EnumProcessModulesFilter
```

**VB Usage**<br />
``` VB Usage
Dim instance As EnumProcessModulesFilter
```

**C++**<br />
``` C++
public enum class EnumProcessModulesFilter
```

**F#**<br />
``` F#
type EnumProcessModulesFilter
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter.Default">**Default**</td><td>0</td><td>Use the default behavior.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter.x86">**x86**</td><td>1</td><td>List the 32-bit modules.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter.x64">**x64**</td><td>2</td><td>List the 64-bit modules.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter.All">**All**</td><td>3</td><td>List all (32-Bit and 64-Bit) modules.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-enumprocessmodulesex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-enumprocessmodulesex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />