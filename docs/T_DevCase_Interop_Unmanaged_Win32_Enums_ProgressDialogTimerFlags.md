# ProgressDialogTimerFlags Enumeration
 

Flags that indicate the action to be taken by the timer of the progress dialog box for <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_Timer">Timer(ProgressDialogTimerFlags, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ProgressDialogTimerFlags
```

**VB**<br />
``` VB
Public Enumeration ProgressDialogTimerFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProgressDialogTimerFlags
```

**C++**<br />
``` C++
public enum class ProgressDialogTimerFlags
```

**F#**<br />
``` F#
type ProgressDialogTimerFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogTimerFlags.Reset">**Reset**</td><td>1</td><td>Resets the timer to zero. Progress will be calculated from the time this method is called.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogTimerFlags.Pause">**Pause**</td><td>2</td><td>Progress has been suspended.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogTimerFlags.Resume">**Resume**</td><td>3</td><td>Progress has been resumed.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-iprogressdialog-timer" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-iprogressdialog-timer</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />