# KeybdEventFlags Enumeration
 

Specifies key behavior for the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_KeybdEvent">KeybdEvent(VirtualKeys, Byte, KeybdEventFlags, UIntPtr)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum KeybdEventFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration KeybdEventFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeybdEventFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class KeybdEventFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type KeybdEventFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeybdEventFlags.NonExtendedKey">**NonExtendedKey**</td><td>0</td><td>The scan code was not preceded by a prefix byte having the value 0xE0 (224).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeybdEventFlags.ExtendedKey">**ExtendedKey**</td><td>1</td><td>The scan code was preceded by a prefix byte having the value 0xE0 (224).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeybdEventFlags.KeyUp">**KeyUp**</td><td>2</td><td>The key is being released. If this flag is not specified, the key is being pressed.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-keybd_event" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-keybd_event</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />