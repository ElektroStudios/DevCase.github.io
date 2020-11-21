# IShellLinkW.GetPath Method 
 

Retrieves the path and file name of a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetPath(
	StringBuilder file,
	int maxPath,
	ref Win32FindDataW refWin32FindData,
	IShellLinkGetPathFlags flags
)
```

**VB**<br />
``` VB
Sub GetPath ( 
	<OutAttribute> file As StringBuilder,
	maxPath As Integer,
	ByRef refWin32FindData As Win32FindDataW,
	flags As IShellLinkGetPathFlags
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim file As StringBuilder
Dim maxPath As Integer
Dim refWin32FindData As Win32FindDataW
Dim flags As IShellLinkGetPathFlags

instance.GetPath(file, maxPath, refWin32FindData, 
	flags)
```

**C++**<br />
``` C++
void GetPath(
	[OutAttribute] StringBuilder^ file, 
	int maxPath, 
	Win32FindDataW% refWin32FindData, 
	IShellLinkGetPathFlags flags
)
```

**F#**<br />
``` F#
abstract GetPath : 
        file : StringBuilder byref * 
        maxPath : int * 
        refWin32FindData : Win32FindDataW byref * 
        flags : IShellLinkGetPathFlags -> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.Text.StringBuilder<br />The address of a buffer that receives the path and file name of the target of the Shell link object.</dd><dt>maxPath</dt><dd>Type: System.Int32<br />The size, in characters, of the buffer pointed to by the pszFile parameter, including the terminating null character. 

 The maximum path size that can be returned is `MAX_PATH`.</dd><dt>refWin32FindData</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">DevCase.Interop.Unmanaged.Win32.Structures.Win32FindDataW</a><br />A pointer to a WIN32_FIND_DATA structure that receives information about the target of the Shell link object. 

 If this parameter is NULL, then no additional information is returned.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IShellLinkGetPathFlags">DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkGetPathFlags</a><br />Flags that specify the type of path information to retrieve.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />