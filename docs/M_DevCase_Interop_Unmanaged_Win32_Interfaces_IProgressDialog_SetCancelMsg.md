# IProgressDialog.SetCancelMsg Method 
 

Sets a message to be displayed if the user cancels the operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetCancelMsg(
	string cancelMsg,
	IntPtr reserved = null
)
```

**VB**<br />
``` VB
Sub SetCancelMsg ( 
	cancelMsg As String,
	Optional reserved As IntPtr = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim cancelMsg As String
Dim reserved As IntPtr

instance.SetCancelMsg(cancelMsg, reserved)
```

**C++**<br />
``` C++
void SetCancelMsg(
	String^ cancelMsg, 
	IntPtr reserved = nullptr
)
```

**F#**<br />
``` F#
abstract SetCancelMsg : 
        cancelMsg : string * 
        ?reserved : IntPtr 
(* Defaults:
        let _reserved = defaultArg reserved null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>cancelMsg</dt><dd>Type: System.String<br />A pointer to a null-terminated Unicode string that contains the message to be displayed.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />Reserved. Set to Zero.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />