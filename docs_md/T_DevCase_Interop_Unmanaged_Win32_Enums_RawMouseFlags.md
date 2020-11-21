# RawMouseFlags Enumeration
 

The mouse state for raw mouse data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum RawMouseFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration RawMouseFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As RawMouseFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class RawMouseFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type RawMouseFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseFlags.MoveRelative">**MoveRelative**</td><td>0</td><td>Mouse movement data is relative to the last mouse position.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseFlags.MoveAbsolute">**MoveAbsolute**</td><td>1</td><td>Mouse movement data is based on absolute position.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseFlags.VirtualDesktop">**VirtualDesktop**</td><td>2</td><td>Mouse coordinates are mapped to the virtual desktop (for a multiple monitor system).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseFlags.AttributesChanged">**AttributesChanged**</td><td>4</td><td>Mouse attributes changed; application needs to query the mouse attributes.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645578%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645578%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />