# ToolbarButtonStates Enumeration
 

Specifies the states a toolbar button can have.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ToolbarButtonStates
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ToolbarButtonStates
```

**VB Usage**<br />
``` VB Usage
Dim instance As ToolbarButtonStates
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ToolbarButtonStates
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ToolbarButtonStates
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.None">**None**</td><td>0</td><td>None.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Checked">**Checked**</td><td>1</td><td>The button has the TBSTYLE_CHECK style and is being clicked.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Pressed">**Pressed**</td><td>2</td><td>The button is being clicked.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Enabled">**Enabled**</td><td>4</td><td>The button accepts user input. A button that does not have this state is grayed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Hidden">**Hidden**</td><td>8</td><td>The button is not visible and cannot receive user input.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Indeterminate">**Indeterminate**</td><td>16</td><td>The button is grayed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Wrap">**Wrap**</td><td>32</td><td>The button is followed by a line break. The button must also have the Enabled state.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Ellipses">**Ellipses**</td><td>64</td><td>The button's text is cut off and an ellipsis is displayed</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarButtonStates.Marked">**Marked**</td><td>128</td><td>The button is marked. The interpretation of a marked item is dependent upon the application..</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/controls/toolbar-button-states" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/controls/toolbar-button-states</a><a href="https://docs.microsoft.com/en-us/windows/desktop/controls/tb-getstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/controls/tb-getstate</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />