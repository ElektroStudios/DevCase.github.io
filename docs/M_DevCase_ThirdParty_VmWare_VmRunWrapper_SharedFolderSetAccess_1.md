# VmRunWrapper.SharedFolderSetAccess Method (VMWareVirtualMachine, String, String, Boolean)
 

Sets the writable/readonly access of a shared folder in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SharedFolderSetAccess(
	VMWareVirtualMachine vm,
	string shareName,
	string hostDirectoryPath,
	bool allowWriteAccess
)
```

**VB**<br />
``` VB
Public Sub SharedFolderSetAccess ( 
	vm As VMWareVirtualMachine,
	shareName As String,
	hostDirectoryPath As String,
	allowWriteAccess As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim shareName As String
Dim hostDirectoryPath As String
Dim allowWriteAccess As Boolean

instance.SharedFolderSetAccess(vm, shareName, 
	hostDirectoryPath, allowWriteAccess)
```

**C++**<br />
``` C++
public:
void SharedFolderSetAccess(
	VMWareVirtualMachine^ vm, 
	String^ shareName, 
	String^ hostDirectoryPath, 
	bool allowWriteAccess
)
```

**F#**<br />
``` F#
member SharedFolderSetAccess : 
        vm : VMWareVirtualMachine * 
        shareName : string * 
        hostDirectoryPath : string * 
        allowWriteAccess : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>shareName</dt><dd>Type: System.String<br />The name of the shared folder.</dd><dt>hostDirectoryPath</dt><dd>Type: System.String<br />The full path to the directory that points the shared folder on the host operating system.</dd><dt>allowWriteAccess</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), allow write access to the shared folder; otherwise, make the shared folder read-only.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderSetAccess">SharedFolderSetAccess Overload</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />