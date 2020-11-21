# IShellLinkW.SetWorkingDirectory Method 
 

Sets the name of the working directory for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetWorkingDirectory(
	string dir
)
```

**VB**<br />
``` VB
Sub SetWorkingDirectory ( 
	dir As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim dir As String

instance.SetWorkingDirectory(dir)
```

**C++**<br />
``` C++
void SetWorkingDirectory(
	String^ dir
)
```

**F#**<br />
``` F#
abstract SetWorkingDirectory : 
        dir : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>dir</dt><dd>Type: System.String<br />The address of a buffer that contains the name of the new working directory.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />