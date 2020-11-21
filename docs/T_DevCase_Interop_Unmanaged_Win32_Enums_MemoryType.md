# MemoryType Enumeration
 

Specifies the type of pages in a memory region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MemoryType
```

**VB**<br />
``` VB
Public Enumeration MemoryType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryType
```

**C++**<br />
``` C++
public enum class MemoryType
```

**F#**<br />
``` F#
type MemoryType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryType.Image">**Image**</td><td>16777216</td><td>Indicates that the memory pages within the region are mapped into the view of an image section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryType.Mapped">**Mapped**</td><td>262144</td><td>Indicates that the memory pages within the region are mapped into the view of a section.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryType.Private">**Private**</td><td>131072</td><td>Indicates that the memory pages within the region are private (that is, not shared by other processes).</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366786(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366786(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />