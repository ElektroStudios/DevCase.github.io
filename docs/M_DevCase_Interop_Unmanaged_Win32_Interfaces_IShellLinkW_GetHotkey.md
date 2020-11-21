# IShellLinkW.GetHotkey Method 
 

Retrieves the hot key for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetHotkey(
	ref ushort refHotkey
)
```

**VB**<br />
``` VB
Sub GetHotkey ( 
	ByRef refHotkey As UShort
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim refHotkey As UShort

instance.GetHotkey(refHotkey)
```

**C++**<br />
``` C++
void GetHotkey(
	unsigned short% refHotkey
)
```

**F#**<br />
``` F#
abstract GetHotkey : 
        refHotkey : uint16 byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refHotkey</dt><dd>Type: System.UInt16<br />The address of the keyboard shortcut. 

 The virtual key code is in the low-order byte, and the hotkey modifier flags are in the high-order byte.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />