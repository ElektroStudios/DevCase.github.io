# IProgressDialog.StartProgressDialog Method 
 

Starts the progress dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void StartProgressDialog(
	[OptionalAttribute] IntPtr hwndParent,
	[OptionalAttribute] Object punkEnableModless,
	ProgressDialogFlags flags,
	IntPtr pvreserved = null
)
```

**VB**<br />
``` VB
Sub StartProgressDialog ( 
	<OptionalAttribute> hwndParent As IntPtr,
	<OptionalAttribute> punkEnableModless As Object,
	flags As ProgressDialogFlags,
	Optional pvreserved As IntPtr = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim hwndParent As IntPtr
Dim punkEnableModless As Object
Dim flags As ProgressDialogFlags
Dim pvreserved As IntPtr

instance.StartProgressDialog(hwndParent, 
	punkEnableModless, flags, pvreserved)
```

**C++**<br />
``` C++
void StartProgressDialog(
	[OptionalAttribute] IntPtr hwndParent, 
	[OptionalAttribute] Object^ punkEnableModless, 
	ProgressDialogFlags flags, 
	IntPtr pvreserved = nullptr
)
```

**F#**<br />
``` F#
abstract StartProgressDialog : 
        [<OptionalAttribute>] hwndParent : IntPtr * 
        [<OptionalAttribute>] punkEnableModless : Object * 
        flags : ProgressDialogFlags * 
        ?pvreserved : IntPtr 
(* Defaults:
        let _pvreserved = defaultArg pvreserved null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>hwndParent (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the dialog box's parent window.</dd><dt>punkEnableModless (Optional)</dt><dd>Type: System.Object<br />Reserved. Set to null.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProgressDialogFlags">DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags</a><br />Flags that control the operation of the progress dialog box.</dd><dt>pvreserved (Optional)</dt><dd>Type: System.IntPtr<br />Reserved. Set to Zero</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />