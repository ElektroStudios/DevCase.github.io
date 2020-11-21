# PowerPlanAccess Enumeration
 

Specifies what will be enumerated by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PowerEnumerate">PowerEnumerate(IntPtr, IntPtr, IntPtr, PowerPlanAccess, UInt32, Guid, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum PowerPlanAccess
```

**VB**<br />
``` VB
Public Enumeration PowerPlanAccess
```

**VB Usage**<br />
``` VB Usage
Dim instance As PowerPlanAccess
```

**C++**<br />
``` C++
public enum class PowerPlanAccess
```

**F#**<br />
``` F#
type PowerPlanAccess
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PowerPlanAccess.Schemes">**Schemes**</td><td>16</td><td>Enumerate power schemes. 

 The `schemeGuid` and `subgroupOfPowerSettingsGuid` parameters will be ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PowerPlanAccess.Subgroups">**Subgroups**</td><td>17</td><td>Enumerate subgroups under `SchemeGuid`. 

 The `subgroupOfPowerSettingsGuid` parameter will be ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PowerPlanAccess.IndividualSettings">**IndividualSettings**</td><td>18</td><td>Enumerate individual power settings under `SchemeGuid\SubgroupOfPowerSettingsGuid`. 

 To enumerate power settings directly under the `SchemeGuid` key, use `NO_SUBGROUP_GUID` as the `subgroupOfPowerSettingsGuid` parameter.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa372730%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa372730%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />