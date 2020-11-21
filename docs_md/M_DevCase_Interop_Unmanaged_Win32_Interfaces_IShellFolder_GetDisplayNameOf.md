# IShellFolder.GetDisplayNameOf Method 
 

Retrieves the display name for the specified file object or subfolder.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
string GetDisplayNameOf(
	PIDL pidl,
	ShellFoldermGetDisplayName flags
)
```

**VB**<br />
``` VB
Function GetDisplayNameOf ( 
	pidl As PIDL,
	flags As ShellFoldermGetDisplayName
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim pidl As PIDL
Dim flags As ShellFoldermGetDisplayName
Dim returnValue As String

returnValue = instance.GetDisplayNameOf(pidl, 
	flags)
```

**C++**<br />
``` C++
String^ GetDisplayNameOf(
	[InAttribute] PIDL^ pidl, 
	ShellFoldermGetDisplayName flags
)
```

**F#**<br />
``` F#
abstract GetDisplayNameOf : 
        pidl : PIDL * 
        flags : ShellFoldermGetDisplayName -> string 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />PIDL that uniquely identifies the file object or subfolder relative to the parent folder.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellFoldermGetDisplayName">DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName</a><br />Flags used to request the type of display name to return.</dd></dl>

#### Return Value
Type: String<br />When this method returns, contains a pointer to a STRRET structure in which to return the display name. 

 The type of name returned in this structure can be the requested type, but the Shell folder might return a different type.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />