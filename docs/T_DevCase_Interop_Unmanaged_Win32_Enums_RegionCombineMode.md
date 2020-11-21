# RegionCombineMode Enumeration
 

Inndicates how two regions will be combined when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CombineRgn">CombineRgn(IntPtr, IntPtr, IntPtr, RegionCombineMode)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum RegionCombineMode
```

**VB**<br />
``` VB
Public Enumeration RegionCombineMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegionCombineMode
```

**C++**<br />
``` C++
public enum class RegionCombineMode
```

**F#**<br />
``` F#
type RegionCombineMode
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode.And">**And**</td><td>1</td><td>Creates the intersection of the two combined regions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode.Or">**Or**</td><td>2</td><td>Creates the union of two combined regions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode.Xor">**Xor**</td><td>3</td><td>Creates the union of two combined regions except for any overlapping areas.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode.Diff">**Diff**</td><td>4</td><td>Combines the parts of the region identified by `hRgnSrc1` parameter that are not part of the region identified by `hRgnSrc2` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode.Copy">**Copy**</td><td>5</td><td>Creates a copy of the region identified by `hRgnSrc1` parameter.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-combinergn" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-combinergn</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />