# IProgressDialog.Timer Method 
 

Resets the progress dialog box timer to zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void Timer(
	ProgressDialogTimerFlags timerAction,
	IntPtr reserved = null
)
```

**VB**<br />
``` VB
Sub Timer ( 
	timerAction As ProgressDialogTimerFlags,
	Optional reserved As IntPtr = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim timerAction As ProgressDialogTimerFlags
Dim reserved As IntPtr

instance.Timer(timerAction, reserved)
```

**C++**<br />
``` C++
void Timer(
	ProgressDialogTimerFlags timerAction, 
	IntPtr reserved = nullptr
)
```

**F#**<br />
``` F#
abstract Timer : 
        timerAction : ProgressDialogTimerFlags * 
        ?reserved : IntPtr 
(* Defaults:
        let _reserved = defaultArg reserved null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>timerAction</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProgressDialogTimerFlags">DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogTimerFlags</a><br />Flags that indicate the action to be taken by the timer.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />Reserved. Set to NULL.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />