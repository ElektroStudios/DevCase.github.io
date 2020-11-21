# HotkeyModifiers Enumeration
 

Specifies a key-modifier to assign for a hotkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum HotkeyModifiers
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration HotkeyModifiers
```

**VB Usage**<br />
``` VB Usage
Dim instance As HotkeyModifiers
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class HotkeyModifiers
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type HotkeyModifiers
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.IO.HotkeyModifiers.None">**None**</td><td>0</td><td>Specifies any modifier.</td></tr><tr><td /><td target="F:DevCase.Core.IO.HotkeyModifiers.Alt">**Alt**</td><td>1</td><td>The `ALT` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Core.IO.HotkeyModifiers.Control">**Control**</td><td>2</td><td>The `CTRL` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Core.IO.HotkeyModifiers.Shift">**Shift**</td><td>4</td><td>The `SHIFT` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Core.IO.HotkeyModifiers.Win">**Win**</td><td>8</td><td>The `WIN` keyboard key.</td></tr><tr><td /><td target="F:DevCase.Core.IO.HotkeyModifiers.NoRepeat">**NoRepeat**</td><td>16384</td><td>Changes the hotkey behavior so that the keyboard auto-repeat does not yield multiple hotkey notifications.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms646309%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms646309%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />