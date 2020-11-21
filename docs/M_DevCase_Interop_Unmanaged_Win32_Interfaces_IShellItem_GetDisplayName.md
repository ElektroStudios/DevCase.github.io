# IShellItem.GetDisplayName Method 
 

Gets the display name of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
StringBuilder GetDisplayName(
	ShellItemGetDisplayName sigdn
)
```

**VB**<br />
``` VB
Function GetDisplayName ( 
	sigdn As ShellItemGetDisplayName
) As StringBuilder
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItem
Dim sigdn As ShellItemGetDisplayName
Dim returnValue As StringBuilder

returnValue = instance.GetDisplayName(sigdn)
```

**C++**<br />
``` C++
StringBuilder^ GetDisplayName(
	ShellItemGetDisplayName sigdn
)
```

**F#**<br />
``` F#
abstract GetDisplayName : 
        sigdn : ShellItemGetDisplayName -> StringBuilder 

```


#### Parameters
&nbsp;<dl><dt>sigdn</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemGetDisplayName">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName</a><br />One of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemGetDisplayName">ShellItemGetDisplayName</a> values that indicates how the name should look.</dd></dl>

#### Return Value
Type: StringBuilder<br />A value that, when this function returns successfully, receives the address of a pointer to the retrieved display name.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />