# SetProcessWorkingSetSizeFlags Enumeration
 

Specifies the enforcement of the minimum and maximum working set sizes. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetProcessWorkingSetSizeEx">SetProcessWorkingSetSizeEx(IntPtr, IntPtr, IntPtr, SetProcessWorkingSetSizeFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SetProcessWorkingSetSizeFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SetProcessWorkingSetSizeFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetProcessWorkingSetSizeFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SetProcessWorkingSetSizeFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SetProcessWorkingSetSizeFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetProcessWorkingSetSizeFlags.QuotaLimitsHardwsMinDisable">**QuotaLimitsHardwsMinDisable**</td><td>2</td><td>The working set may fall below the minimum working set limit if memory demands are high. 

 This flag cannot be used With QuotaLimitsHardwsMinEnable.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetProcessWorkingSetSizeFlags.QuotaLimitsHardwsMinEnable">**QuotaLimitsHardwsMinEnable**</td><td>1</td><td>The working set will not fall below the minimum working set limit. 

 This flag cannot be used With QuotaLimitsHardwsMinDisable.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetProcessWorkingSetSizeFlags.QuotaLimitsHardwsMaxDisable">**QuotaLimitsHardwsMaxDisable**</td><td>8</td><td>The working set may exceed the maximum working set limit if there is abundant memory. 

 This flag cannot be used With QuotaLimitsHardwsMaxEnable.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetProcessWorkingSetSizeFlags.QuotaLimitsHardwsMaxEnable">**QuotaLimitsHardwsMaxEnable**</td><td>4</td><td>The working set will not exceed the maximum working set limit. 

 This flag cannot be used With QuotaLimitsHardwsMaxDisable.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-setprocessworkingsetsizeex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-setprocessworkingsetsizeex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />