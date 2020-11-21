# IShellLinkW.SetHotkey Method 
 

Sets a hot key for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetHotkey(
	ushort hotkey
)
```

**VB**<br />
``` VB
Sub SetHotkey ( 
	hotkey As UShort
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim hotkey As UShort

instance.SetHotkey(hotkey)
```

**C++**<br />
``` C++
void SetHotkey(
	unsigned short hotkey
)
```

**F#**<br />
``` F#
abstract SetHotkey : 
        hotkey : uint16 -> unit 

```


#### Parameters
&nbsp;<dl><dt>hotkey</dt><dd>Type: System.UInt16<br />The new keyboard shortcut. 

 The virtual key code is in the low-order byte, and the modifier flags are in the high-order byte.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />