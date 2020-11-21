# IShellLinkW.GetIconLocation Method 
 

Retrieves the location (path and index) of the icon for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetIconLocation(
	StringBuilder iconPath,
	int iconPathSize,
	ref int refIconIndex
)
```

**VB**<br />
``` VB
Sub GetIconLocation ( 
	<OutAttribute> iconPath As StringBuilder,
	iconPathSize As Integer,
	ByRef refIconIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim iconPath As StringBuilder
Dim iconPathSize As Integer
Dim refIconIndex As Integer

instance.GetIconLocation(iconPath, iconPathSize, 
	refIconIndex)
```

**C++**<br />
``` C++
void GetIconLocation(
	[OutAttribute] StringBuilder^ iconPath, 
	int iconPathSize, 
	int% refIconIndex
)
```

**F#**<br />
``` F#
abstract GetIconLocation : 
        iconPath : StringBuilder byref * 
        iconPathSize : int * 
        refIconIndex : int byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>iconPath</dt><dd>Type: System.Text.StringBuilder<br />The address of a buffer that receives the path of the file containing the icon.</dd><dt>iconPathSize</dt><dd>Type: System.Int32<br />The maximum number of characters to copy to the buffer pointed to by the *iconPath* parameter.</dd><dt>refIconIndex</dt><dd>Type: System.Int32<br />The address of a value that receives the index of the icon.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />