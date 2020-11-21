# IShellFolder.EnumObjects Method 
 

Enables a client to determine the contents of a folder by creating an item identifier enumeration object and returning its IEnumIDList interface. 

 The methods supported by that interface can then be used to enumerate the folder's contents.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
IEnumIDList EnumObjects(
	IntPtr hwndOwner,
	ShellFolderEnumObjectsFlags flags
)
```

**VB**<br />
``` VB
Function EnumObjects ( 
	hwndOwner As IntPtr,
	flags As ShellFolderEnumObjectsFlags
) As IEnumIDList
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim hwndOwner As IntPtr
Dim flags As ShellFolderEnumObjectsFlags
Dim returnValue As IEnumIDList

returnValue = instance.EnumObjects(hwndOwner, 
	flags)
```

**C++**<br />
``` C++
IEnumIDList^ EnumObjects(
	IntPtr hwndOwner, 
	ShellFolderEnumObjectsFlags flags
)
```

**F#**<br />
``` F#
abstract EnumObjects : 
        hwndOwner : IntPtr * 
        flags : ShellFolderEnumObjectsFlags -> IEnumIDList 

```


#### Parameters
&nbsp;<dl><dt>hwndOwner</dt><dd>Type: System.IntPtr<br />If user input is required to perform the enumeration, this window handle should be used by the enumeration object as the parent window to take user input. 

 An example would be a dialog box to ask for a password or prompt the user to insert a CD or floppy disk. 

 If *hwndOwner* is set to NULL, the enumerator should not post any messages, and if user input is required, it should silently fail.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellFolderEnumObjectsFlags">DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags</a><br />Flags indicating which items to include in the enumeration.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList</a><br />The address that receives a pointer to the IEnumIDList interface of the enumeration object created by this method. 

 If an error occurs or no suitable subobjects are found, ppenumIDList is set to NULL.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />