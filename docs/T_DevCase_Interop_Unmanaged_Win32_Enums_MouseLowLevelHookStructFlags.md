# MouseLowLevelHookStructFlags Enumeration
 

An application can use the following values to test a mouse low-level flags. 

 Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Flags">Flags</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MouseLowLevelHookStructFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MouseLowLevelHookStructFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseLowLevelHookStructFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MouseLowLevelHookStructFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MouseLowLevelHookStructFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseLowLevelHookStructFlags.Injected">**Injected**</td><td>1</td><td>Test the event-injected (from any process) flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseLowLevelHookStructFlags.LowerILInjected">**LowerILInjected**</td><td>2</td><td>Test the event-injected (from a process running at lower integrity level) flag.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644970%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644970%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />