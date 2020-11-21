# IShellLinkW.GetWorkingDirectory Method 
 

Retrieves the name of the working directory for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetWorkingDirectory(
	StringBuilder dir,
	int maxPath
)
```

**VB**<br />
``` VB
Sub GetWorkingDirectory ( 
	<OutAttribute> dir As StringBuilder,
	maxPath As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim dir As StringBuilder
Dim maxPath As Integer

instance.GetWorkingDirectory(dir, maxPath)
```

**C++**<br />
``` C++
void GetWorkingDirectory(
	[OutAttribute] StringBuilder^ dir, 
	int maxPath
)
```

**F#**<br />
``` F#
abstract GetWorkingDirectory : 
        dir : StringBuilder byref * 
        maxPath : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>dir</dt><dd>Type: System.Text.StringBuilder<br />The address of a buffer that receives the name of the working directory.</dd><dt>maxPath</dt><dd>Type: System.Int32<br />The maximum number of characters to copy to the buffer pointed to by the pszDir parameter. 

 The name of the working directory is truncated if it is longer than the maximum specified by this parameter.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />