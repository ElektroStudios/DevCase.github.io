# IShellLinkW.SetDescription Method 
 

Sets the description for a Shell link object. The description can be any application-defined string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetDescription(
	string name
)
```

**VB**<br />
``` VB
Sub SetDescription ( 
	name As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim name As String

instance.SetDescription(name)
```

**C++**<br />
``` C++
void SetDescription(
	String^ name
)
```

**F#**<br />
``` F#
abstract SetDescription : 
        name : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />A pointer to a buffer containing the new description string.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />