# IProgressDialog.SetTitle Method 
 

Sets the title of the progress dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetTitle(
	string title
)
```

**VB**<br />
``` VB
Sub SetTitle ( 
	title As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim title As String

instance.SetTitle(title)
```

**C++**<br />
``` C++
void SetTitle(
	String^ title
)
```

**F#**<br />
``` F#
abstract SetTitle : 
        title : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>title</dt><dd>Type: System.String<br />A pointer to a null-terminated Unicode string that contains the dialog box title.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />