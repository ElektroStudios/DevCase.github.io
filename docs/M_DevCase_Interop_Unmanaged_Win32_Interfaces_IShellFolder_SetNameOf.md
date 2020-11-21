# IShellFolder.SetNameOf Method 
 

Sets the display name of a file object or subfolder, changing the item identifier in the process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetNameOf(
	IntPtr hwndOwner,
	PIDL pidl,
	string name,
	ShellFoldermGetDisplayName flags,
	ref PIDL refPidlOut
)
```

**VB**<br />
``` VB
Sub SetNameOf ( 
	hwndOwner As IntPtr,
	pidl As PIDL,
	name As String,
	flags As ShellFoldermGetDisplayName,
	ByRef refPidlOut As PIDL
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim hwndOwner As IntPtr
Dim pidl As PIDL
Dim name As String
Dim flags As ShellFoldermGetDisplayName
Dim refPidlOut As PIDL

instance.SetNameOf(hwndOwner, pidl, name, 
	flags, refPidlOut)
```

**C++**<br />
``` C++
void SetNameOf(
	IntPtr hwndOwner, 
	[InAttribute] PIDL^ pidl, 
	String^ name, 
	ShellFoldermGetDisplayName flags, 
	PIDL^% refPidlOut
)
```

**F#**<br />
``` F#
abstract SetNameOf : 
        hwndOwner : IntPtr * 
        pidl : PIDL * 
        name : string * 
        flags : ShellFoldermGetDisplayName * 
        refPidlOut : PIDL byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>hwndOwner</dt><dd>Type: System.IntPtr<br />A handle to the owner window of any dialog or message box that the client displays.</dd><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A pointer to an ITEMIDLIST structure that uniquely identifies the file object or subfolder relative to the parent folder. 

 The structure must contain exactly one SHITEMID structure followed by a terminating zero.</dd><dt>name</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the new display name.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellFoldermGetDisplayName">DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName</a><br />Flags that indicate the type of name specified by the *name* parameter.</dd><dt>refPidlOut</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />Optional. If specified, the address of a pointer to an ITEMIDLIST structure that receives the ITEMIDLIST of the renamed item. 

 The caller requests this value by passing a non-null *refPidlOut*. 

 Implementations of IShellFolder::SetNameOf must return a pointer to the new ITEMIDLIST in the *refPidlOut* parameter.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />