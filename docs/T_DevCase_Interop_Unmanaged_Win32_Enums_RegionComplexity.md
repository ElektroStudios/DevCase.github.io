# RegionComplexity Enumeration
 

specifies the complexity of a region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum RegionComplexity
```

**VB**<br />
``` VB
Public Enumeration RegionComplexity
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegionComplexity
```

**C++**<br />
``` C++
public enum class RegionComplexity
```

**F#**<br />
``` F#
type RegionComplexity
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionComplexity.Error">**Error**</td><td>0</td><td>The specified window does not have a region, or an error occurred while attempting to return the region.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionComplexity.NullRegion">**NullRegion**</td><td>1</td><td>The region is empty.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionComplexity.SimpleRegion">**SimpleRegion**</td><td>2</td><td>The region is a single rectangle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionComplexity.ComplexRegion">**ComplexRegion**</td><td>3</td><td>The region is more than one rectangle.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowrgnbox" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowrgnbox</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />