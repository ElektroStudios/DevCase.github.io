# ProgressDialogFlags Enumeration
 

Flags that control the operation of the progress dialog box for <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_StartProgressDialog">StartProgressDialog(IntPtr, Object, ProgressDialogFlags, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ProgressDialogFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ProgressDialogFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProgressDialogFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ProgressDialogFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ProgressDialogFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.Normal">**Normal**</td><td>0</td><td>Normal progress dialog box behavior.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.Modal">**Modal**</td><td>1</td><td>The progress dialog box will be modal to the window specified by hwndParent. 

 By default, a progress dialog box is modeless.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.AutoTime">**AutoTime**</td><td>2</td><td>Automatically estimate the remaining time and display the estimate on line 3.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.NoTime">**NoTime**</td><td>4</td><td>Do not show the "time remaining" text.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.NoMinimize">**NoMinimize**</td><td>8</td><td>Do not display a minimize button on the dialog box's caption bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.NoProgressBar">**NoProgressBar**</td><td>16</td><td>Do not display a progress bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.MarqueeProgress">**MarqueeProgress**</td><td>32</td><td>Sets the progress bar to marquee mode.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags.NoCancel">**NoCancel**</td><td>64</td><td>Do not display a cancel button.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-iprogressdialog-startprogressdialog" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-iprogressdialog-startprogressdialog</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />