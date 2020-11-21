# IShellLinkW.SetRelativePath Method 
 

Sets the relative path to the Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetRelativePath(
	string pathRelative,
	int reserved
)
```

**VB**<br />
``` VB
Sub SetRelativePath ( 
	pathRelative As String,
	reserved As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim pathRelative As String
Dim reserved As Integer

instance.SetRelativePath(pathRelative, 
	reserved)
```

**C++**<br />
``` C++
void SetRelativePath(
	String^ pathRelative, 
	int reserved
)
```

**F#**<br />
``` F#
abstract SetRelativePath : 
        pathRelative : string * 
        reserved : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>pathRelative</dt><dd>Type: System.String<br />The address of a buffer that contains the fully-qualified path of the shortcut file, relative to which the shortcut resolution should be performed. 

 It should be a file name, not a folder name.</dd><dt>reserved</dt><dd>Type: System.Int32<br />Reserved. 

 Set this parameter to zero.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />