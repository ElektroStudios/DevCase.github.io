# RawMouseButtons Enumeration
 

The mouse buttons data for raw mouse input.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum RawMouseButtons
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration RawMouseButtons
```

**VB Usage**<br />
``` VB Usage
Dim instance As RawMouseButtons
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class RawMouseButtons
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type RawMouseButtons
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.None">**None**</td><td>0</td><td>No button.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.LeftDown">**LeftDown**</td><td>1</td><td>Left button changed to down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.LeftUp">**LeftUp**</td><td>2</td><td>Left button changed to up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.RightDown">**RightDown**</td><td>4</td><td>Right button changed to down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.RightUp">**RightUp**</td><td>8</td><td>Right button changed to up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.MiddleDown">**MiddleDown**</td><td>16</td><td>Middle button changed to down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.MiddleUp">**MiddleUp**</td><td>32</td><td>Middle button changed to up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.XButton1Down">**XButton1Down**</td><td>64</td><td>XBUTTON1 changed to down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.XButton1Up">**XButton1Up**</td><td>128</td><td>XBUTTON1 changed to up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.XButton2Down">**XButton2Down**</td><td>256</td><td>XBUTTON2 changed to down.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.XButton2Up">**XButton2Up**</td><td>512</td><td>XBUTTON2 changed to up.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.RawMouseButtons.MouseWheel">**MouseWheel**</td><td>1024</td><td>Mouse wheel moved. 

 The wheel delta is stored in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawMouseButtonData_ButtonData">ButtonData</a>.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645578%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645578%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />