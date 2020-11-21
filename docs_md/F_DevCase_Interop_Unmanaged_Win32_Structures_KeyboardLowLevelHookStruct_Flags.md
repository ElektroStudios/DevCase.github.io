# KeyboardLowLevelHookStruct.Flags Field
 

The extended-key flag, event-injected flags, context code, and transition-state flag. 

 This member is specified as follows. An application can use the following values to test the keystroke flags. 

 Testing `LLKHF_INJECTED` (bit 4) will tell you whether the event was injected. If it was, then testing `LLKHF_LOWER_IL_INJECTED` (bit 1) will tell you whether or not the event was injected from a process running at lower integrity level.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public KeyboardLowLevelHookStructFlags Flags
```

**VB**<br />
``` VB
Public Flags As KeyboardLowLevelHookStructFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardLowLevelHookStruct
Dim value As KeyboardLowLevelHookStructFlags

value = instance.Flags

instance.Flags = value
```

**C++**<br />
``` C++
public:
KeyboardLowLevelHookStructFlags Flags
```

**F#**<br />
``` F#
val mutable Flags: KeyboardLowLevelHookStructFlags
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardLowLevelHookStructFlags">KeyboardLowLevelHookStructFlags</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct">KeyboardLowLevelHookStruct Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />