# IShellLinkW.GetArguments Method 
 

Retrieves the command-line arguments associated with a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetArguments(
	StringBuilder args,
	int maxPath
)
```

**VB**<br />
``` VB
Sub GetArguments ( 
	<OutAttribute> args As StringBuilder,
	maxPath As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim args As StringBuilder
Dim maxPath As Integer

instance.GetArguments(args, maxPath)
```

**C++**<br />
``` C++
void GetArguments(
	[OutAttribute] StringBuilder^ args, 
	int maxPath
)
```

**F#**<br />
``` F#
abstract GetArguments : 
        args : StringBuilder byref * 
        maxPath : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>args</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer that, when this method returns successfully, receives the command-line arguments.</dd><dt>maxPath</dt><dd>Type: System.Int32<br />The maximum number of characters that can be copied to the buffer supplied by the pszArgs parameter. 

 In the case of a Unicode string, there is no limitation on maximum string length. 

 In the case of an ANSI string, the maximum length of the returned string varies depending on the version of Windows.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />