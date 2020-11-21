# IShellItem.Compare Method 
 

Compares two <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> objects.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
int Compare(
	IShellItem psi,
	ShellItemCompareHint hint
)
```

**VB**<br />
``` VB
Function Compare ( 
	psi As IShellItem,
	hint As ShellItemCompareHint
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItem
Dim psi As IShellItem
Dim hint As ShellItemCompareHint
Dim returnValue As Integer

returnValue = instance.Compare(psi, hint)
```

**C++**<br />
``` C++
int Compare(
	IShellItem^ psi, 
	ShellItemCompareHint hint
)
```

**F#**<br />
``` F#
abstract Compare : 
        psi : IShellItem * 
        hint : ShellItemCompareHint -> int 

```


#### Parameters
&nbsp;<dl><dt>psi</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> object to compare with the existing <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> object.</dd><dt>hint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemCompareHint">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemCompareHint</a><br />One of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemCompareHint">ShellItemCompareHint</a> values that determines how to perform the comparison.</dd></dl>

#### Return Value
Type: Int32<br />This parameter receives the result of the comparison. 

 If the two items are the same this parameter equals zero; if they are different the parameter is nonzero.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />