# MouseEventFlags Enumeration
 

Specifies a mouse motion event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MouseEventFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MouseEventFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseEventFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MouseEventFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MouseEventFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.Absolute">**Absolute**</td><td>32768</td><td>The x and y parameters contain normalized absolute coordinates. 

 If not set, those parameters contain relative data: the change in position since the last reported position. 

 This flag can be set, or not set, regardless of what kind of mouse or mouse-like device, if any, is connected to the system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.LeftDown">**LeftDown**</td><td>2</td><td>The left button is down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.LeftUp">**LeftUp**</td><td>4</td><td>The left button is up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.MiddleDown">**MiddleDown**</td><td>32</td><td>The middle button is down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.MiddleUp">**MiddleUp**</td><td>64</td><td>The middle button is up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.Move">**Move**</td><td>1</td><td>Movement occurred.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.RightDown">**RightDown**</td><td>8</td><td>The right button is down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.RightUp">**RightUp**</td><td>16</td><td>The right button is up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.XDown">**XDown**</td><td>128</td><td>An X button was pressed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.XUp">**XUp**</td><td>256</td><td>An X button was released.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.Wheel">**Wheel**</td><td>2048</td><td>The wheel button is rotated.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags.HWheel">**HWheel**</td><td>4096</td><td>The wheel button is tilted.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646260%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646260%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />