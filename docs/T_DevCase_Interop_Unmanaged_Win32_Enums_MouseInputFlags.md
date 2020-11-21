# MouseInputFlags Enumeration
 

A set of bit flags that specify various aspects of mouse motion and button clicks. 

 Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Flags">Flags</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MouseInputFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MouseInputFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseInputFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MouseInputFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MouseInputFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.Absolute">**Absolute**</td><td>32768</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_X">X</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Y">Y</a> members contain normalized absolute coordinates. 

 If the flag is not set, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_X">X</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_Y">Y</a> contain relative data (the change in position since the last reported position). 

 This flag can be set, or not set, regardless of what kind of mouse or other pointing device, if any, is connected to the system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.Move">**Move**</td><td>1</td><td>Movement occurred.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.MoveNoCoalesce">**MoveNoCoalesce**</td><td>8192</td><td>The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseMove</a> messages will not be coalesced. 

 The default behavior is to coalesce <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseMove</a> messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.LeftDown">**LeftDown**</td><td>2</td><td>The left button was pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.LeftUp">**LeftUp**</td><td>4</td><td>The left button was released.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.RightDown">**RightDown**</td><td>8</td><td>The right button was pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.RightUp">**RightUp**</td><td>16</td><td>The right button was released.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.MiddleDown">**MiddleDown**</td><td>32</td><td>The middle button was pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.MiddleUp">**MiddleUp**</td><td>64</td><td>The middle button was released.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.VirtualDesk">**VirtualDesk**</td><td>16384</td><td>Maps coordinates to the entire desktop. 

 Must be used in combination with Absolute.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.Wheel">**Wheel**</td><td>2048</td><td>The wheel was moved, if the mouse has a wheel. 

 The amount of movement is specified in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_MouseData">MouseData</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.HWheel">**HWheel**</td><td>4096</td><td>The wheel was moved horizontally, if the mouse has a wheel. 

 The amount of movement is specified in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseInput_MouseData">MouseData</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.XDown">**XDown**</td><td>128</td><td>An X button was pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseInputFlags.XUp">**XUp**</td><td>256</td><td>An X button was released.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646273%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646273%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />