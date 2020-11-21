# KeyboardInputFlags Enumeration
 

Specifies various aspects of a keystroke. 

 Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum KeyboardInputFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration KeyboardInputFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardInputFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class KeyboardInputFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type KeyboardInputFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardInputFlags.ExtendedKey">**ExtendedKey**</td><td>1</td><td>If specified, the scan code was preceded by a prefix byte that has the value `0xE0` (`224`).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardInputFlags.KeyDown">**KeyDown**</td><td>0</td><td>If specified, the key is being pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardInputFlags.KeyUp">**KeyUp**</td><td>2</td><td>If specified, the key is being released. 

 If not specified, the key is being pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardInputFlags.ScanCode">**ScanCode**</td><td>8</td><td>If specified, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ScanCode">ScanCode</a> identifies the key and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_VirtualKey">VirtualKey</a> is ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardInputFlags.Unicode">**Unicode**</td><td>4</td><td>If specified, the system synthesizes a `VK_PACKET` keystroke. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_VirtualKey">VirtualKey</a> parameter must be `0`. 

 This flag can only be combined with the KeyUp flag.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646271%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646271%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />