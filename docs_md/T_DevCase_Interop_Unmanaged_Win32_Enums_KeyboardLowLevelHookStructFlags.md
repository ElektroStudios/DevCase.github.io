# KeyboardLowLevelHookStructFlags Enumeration
 

An application can use the following values to test the keystroke flags of a keyboard low-level hook. 

 Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardLowLevelHookStruct_Flags">Flags</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum KeyboardLowLevelHookStructFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration KeyboardLowLevelHookStructFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardLowLevelHookStructFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class KeyboardLowLevelHookStructFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type KeyboardLowLevelHookStructFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLowLevelHookStructFlags.Extended">**Extended**</td><td>1</td><td>Test the extended-key (`WIN` key) flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLowLevelHookStructFlags.LowerILInjected">**LowerILInjected**</td><td>2</td><td>Test the event-injected (from a process running at lower integrity level) flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLowLevelHookStructFlags.Injected">**Injected**</td><td>16</td><td>Test the event-injected (from any process) flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLowLevelHookStructFlags.AltDown">**AltDown**</td><td>32</td><td>Test the context code.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLowLevelHookStructFlags.Up">**Up**</td><td>128</td><td>Test the transition-state flag.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa374905%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />