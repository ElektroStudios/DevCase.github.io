# FlashWindowFlags Enumeration
 

Specifies the flash status flags for a window. 

 Flags combination for `DwFlags` parameter of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo">FlashWindowInfo</a> structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum FlashWindowFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration FlashWindowFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As FlashWindowFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class FlashWindowFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type FlashWindowFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags.Stop">**Stop**</td><td>0</td><td>Stop flashing. 

 The system restores the window to its original state.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags.Caption">**Caption**</td><td>1</td><td>Flash the window caption.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags.TaskBar">**TaskBar**</td><td>2</td><td>Flash the taskbar button.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags.All">**All**</td><td>3</td><td>Flash both the window caption and taskbar button. 

 This is equivalent to setting the Caption + TaskBar flags.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags.UntilStop">**UntilStop**</td><td>4</td><td>Flash continuously, until the Stop flag is set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FlashWindowFlags.UntilForeground">**UntilForeground**</td><td>12</td><td>Flash continuously until the window comes to the foreground.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />