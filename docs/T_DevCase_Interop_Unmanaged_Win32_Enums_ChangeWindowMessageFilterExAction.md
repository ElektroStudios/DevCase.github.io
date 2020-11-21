# ChangeWindowMessageFilterExAction Enumeration
 

Specifies the action to be performed by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ChangeWindowMessageFilterExAction
```

**VB**<br />
``` VB
Public Enumeration ChangeWindowMessageFilterExAction
```

**VB Usage**<br />
``` VB Usage
Dim instance As ChangeWindowMessageFilterExAction
```

**C++**<br />
``` C++
public enum class ChangeWindowMessageFilterExAction
```

**F#**<br />
``` F#
type ChangeWindowMessageFilterExAction
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeWindowMessageFilterExAction.Reset">**Reset**</td><td>0</td><td>Resets the window message filter to the default. 

 Any message allowed globally or process-wide will get through, but any message not included in those two categories, and which comes from a lower privileged process, will be blocked.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeWindowMessageFilterExAction.Add">**Add**</td><td>1</td><td>Allows the message through the filter. 

 This enables the message to be received, regardless of the source of the message, even it comes from a lower privileged process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ChangeWindowMessageFilterExAction.Remove">**Remove**</td><td>2</td><td>Blocks the message to be delivered if it comes from a lower privileged process, unless the message is allowed process-wide by using the `ChangeWindowMessageFilter` function or globally.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd388202%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd388202%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />