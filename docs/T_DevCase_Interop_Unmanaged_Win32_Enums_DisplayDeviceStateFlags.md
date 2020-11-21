# DisplayDeviceStateFlags Enumeration
 

Device state flags. 

 Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DisplayDevice_StateFlags">StateFlags</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum DisplayDeviceStateFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration DisplayDeviceStateFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As DisplayDeviceStateFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class DisplayDeviceStateFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type DisplayDeviceStateFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.AttachedToDesktop">**AttachedToDesktop**</td><td>1</td><td>The device is part of the desktop.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.MultiDriver">**MultiDriver**</td><td>2</td><td>Not documented.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.PrimaryDevice">**PrimaryDevice**</td><td>4</td><td>The primary desktop is on the device. 

 For a system with a single display card, this is always set. 

 For a system with multiple display cards, only one device can have this set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.MirroringDriver">**MirroringDriver**</td><td>8</td><td>Represents a pseudo device used to mirror application drawing for remoting or other purposes. 

 An invisible pseudo monitor is associated with this device. For example, `NetMeeting` uses it. 

 Note that `GetSystemMetrics` (`SM_MONITORS`) only accounts for visible display monitors.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.VgaCompatible">**VgaCompatible**</td><td>16</td><td>The device is VGA compatible.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.Removable">**Removable**</td><td>32</td><td>The device is removable; it cannot be the primary display.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.ModesPruned">**ModesPruned**</td><td>134217728</td><td>The device has more display modes than its output devices support.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.Remote">**Remote**</td><td>67108864</td><td>Not documented.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DisplayDeviceStateFlags.Disconnect">**Disconnect**</td><td>33554432</td><td>Not documented.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183569%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183569%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />