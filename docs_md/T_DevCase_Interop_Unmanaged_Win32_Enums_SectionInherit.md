# SectionInherit Enumeration
 

Specifies how the view of a section object is to be shared with child processes when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtMapViewOfSection">NtMapViewOfSection(IntPtr, SafeProcessHandle, IntPtr, IntPtr, IntPtr, Int64, UIntPtr, SectionInherit, MemoryAllocationType, MemoryProtectionOptions)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum SectionInherit
```

**VB**<br />
``` VB
Public Enumeration SectionInherit
```

**VB Usage**<br />
``` VB Usage
Dim instance As SectionInherit
```

**C++**<br />
``` C++
public enum class SectionInherit
```

**F#**<br />
``` F#
type SectionInherit
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionInherit.ViewShare">**ViewShare**</td><td>1</td><td>The view of the section will be mapped into any child processes that are created in the future.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SectionInherit.ViewUnmap">**ViewUnmap**</td><td>2</td><td>The view of the section will not be mapped into child processes.</td></tr></table>

## Remarks
<a href="http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/NT%20Objects/Section/SECTION_INHERIT.html" target="_blank">http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/NT%20Objects/Section/SECTION_INHERIT.html</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />