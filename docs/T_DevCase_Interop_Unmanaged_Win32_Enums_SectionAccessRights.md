# SectionAccessRights Enumeration
 

Specifies access rights for section objects.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SectionAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SectionAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As SectionAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SectionAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SectionAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.Query">**Query**</td><td>1</td><td>Query the section object for information about the section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.MapWrite">**MapWrite**</td><td>2</td><td>Write views of the section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.MapRead">**MapRead**</td><td>4</td><td>Read views of the section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.MapExecute">**MapExecute**</td><td>8</td><td>Execute views of the section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.ExtendSize">**ExtendSize**</td><td>16</td><td>Dynamically extend the size of the section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.MapExecuteExplicit">**MapExecuteExplicit**</td><td>32</td><td>**UNDOCUMENTED** 

 ( This flag is not included in AllAccess )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionAccessRights.AllAccess">**AllAccess**</td><td>983071</td><td>Combines all possible access rights for a section object.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwmapviewofsection" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-Zwmapviewofsection</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />