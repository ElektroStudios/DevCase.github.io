# IShellLinkW.SetIconLocation Method 
 

Sets the location (path and index) of the icon for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetIconLocation(
	string iconPath,
	int iconIndex
)
```

**VB**<br />
``` VB
Sub SetIconLocation ( 
	iconPath As String,
	iconIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim iconPath As String
Dim iconIndex As Integer

instance.SetIconLocation(iconPath, iconIndex)
```

**C++**<br />
``` C++
void SetIconLocation(
	String^ iconPath, 
	int iconIndex
)
```

**F#**<br />
``` F#
abstract SetIconLocation : 
        iconPath : string * 
        iconIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>iconPath</dt><dd>Type: System.String<br />The address of a buffer to contain the path of the file containing the icon.</dd><dt>iconIndex</dt><dd>Type: System.Int32<br />The index of the icon.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />