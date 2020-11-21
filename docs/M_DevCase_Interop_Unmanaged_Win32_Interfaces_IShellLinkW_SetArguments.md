# IShellLinkW.SetArguments Method 
 

Sets the command-line arguments for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetArguments(
	string args
)
```

**VB**<br />
``` VB
Sub SetArguments ( 
	args As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim args As String

instance.SetArguments(args)
```

**C++**<br />
``` C++
void SetArguments(
	String^ args
)
```

**F#**<br />
``` F#
abstract SetArguments : 
        args : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>args</dt><dd>Type: System.String<br />A pointer to a buffer that contains the new command-line arguments. 

 In the case of a Unicode string, there is no limitation on maximum string length. 

 In the case of an ANSI string, the maximum length of the returned string varies depending on the version of Windows.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />