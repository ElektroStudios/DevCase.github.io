# IShellLinkW.GetDescription Method 
 

Retrieves the description string for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetDescription(
	StringBuilder name,
	int maxName
)
```

**VB**<br />
``` VB
Sub GetDescription ( 
	<OutAttribute> name As StringBuilder,
	maxName As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim name As StringBuilder
Dim maxName As Integer

instance.GetDescription(name, maxName)
```

**C++**<br />
``` C++
void GetDescription(
	[OutAttribute] StringBuilder^ name, 
	int maxName
)
```

**F#**<br />
``` F#
abstract GetDescription : 
        name : StringBuilder byref * 
        maxName : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer that receives the description string.</dd><dt>maxName</dt><dd>Type: System.Int32<br />The maximum number of characters to copy to the buffer pointed to by the pszName parameter.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />