# IShellLinkW.SetPath Method 
 

Sets the path and file name of a Shell link object

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetPath(
	string file
)
```

**VB**<br />
``` VB
Sub SetPath ( 
	file As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim file As String

instance.SetPath(file)
```

**C++**<br />
``` C++
void SetPath(
	String^ file
)
```

**F#**<br />
``` F#
abstract SetPath : 
        file : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />The address of a buffer that contains the new path.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />