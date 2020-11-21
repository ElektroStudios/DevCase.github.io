# ToolBarButtonInfoMask Enumeration
 

Specifies which members contain valid information. 

 For <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Mask">Mask</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_Mask">Mask</a> members.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ToolBarButtonInfoMask
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ToolBarButtonInfoMask
```

**VB Usage**<br />
``` VB Usage
Dim instance As ToolBarButtonInfoMask
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ToolBarButtonInfoMask
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ToolBarButtonInfoMask
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.ImageIndex">**ImageIndex**</td><td>1</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_ImageIndex">ImageIndex</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_ImageIndex">ImageIndex</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.Text">**Text**</td><td>2</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Text">Text</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_Text">Text</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.State">**State**</td><td>4</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_State">State</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_State">State</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.Style">**Style**</td><td>8</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Style">Style</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_Style">Style</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.LParam">**LParam**</td><td>16</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_lParam">lParam</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_lParam">lParam</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.CommandId">**CommandId**</td><td>32</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_CommandId">CommandId</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_CommandId">CommandId</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.TextSize">**TextSize**</td><td>64</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_TextSize">TextSize</a> / <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_TextSize">TextSize</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolBarButtonInfoMask.ByIndex">**ByIndex**</td><td>2147483648</td><td>Specifies that the wParam when sending <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ToolbarMessages">GetButtonInfoAnsi</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ToolbarMessages">GetButtonInfoUnicode</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ToolbarMessages">SetButtonInfoAnsi</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ToolbarMessages">SetButtonInfounicode</a> is a button index, not a command id.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb760478%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb760478%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />