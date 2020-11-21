# MouseLowLevelHookStruct.Flags Field
 

The extended-key flag, event-injected flags, context code, and transition-state flag. 

 This member is specified as follows. An application can use the following values to test the mouse flags. 

 Testing `LLKHF_INJECTED` (bit 4) will tell you whether the event was injected. If it was, then testing `LLKHF_LOWER_IL_INJECTED` (bit 1) will tell you whether or not the event was injected from a process running at lower integrity level.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseLowLevelHookStructFlags Flags
```

**VB**<br />
``` VB
Public Flags As MouseLowLevelHookStructFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseLowLevelHookStruct
Dim value As MouseLowLevelHookStructFlags

value = instance.Flags

instance.Flags = value
```

**C++**<br />
``` C++
public:
MouseLowLevelHookStructFlags Flags
```

**F#**<br />
``` F#
val mutable Flags: MouseLowLevelHookStructFlags
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseLowLevelHookStructFlags">MouseLowLevelHookStructFlags</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct">MouseLowLevelHookStruct Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />