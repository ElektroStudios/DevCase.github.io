# NativeHotkeyModifiers Enumeration
 

Specifies a key-modifier to assign for a hotkey.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum NativeHotkeyModifiers
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration NativeHotkeyModifiers
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeHotkeyModifiers
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class NativeHotkeyModifiers
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type NativeHotkeyModifiers
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeHotkeyModifiers.None">**None**</td><td>0</td><td>Specifies any modifier.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeHotkeyModifiers.Alt">**Alt**</td><td>1</td><td>The `ALT` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeHotkeyModifiers.Control">**Control**</td><td>2</td><td>The `CTRL` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeHotkeyModifiers.Shift">**Shift**</td><td>4</td><td>The `SHIFT` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeHotkeyModifiers.Win">**Win**</td><td>8</td><td>The `WIN` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeHotkeyModifiers.NoRepeat">**NoRepeat**</td><td>16384</td><td>Changes the hotkey behavior so that the keyboard auto-repeat does not yield multiple hotkey notifications.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms646309%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms646309%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />