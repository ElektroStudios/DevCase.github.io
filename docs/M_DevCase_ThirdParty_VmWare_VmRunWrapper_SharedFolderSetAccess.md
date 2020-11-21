# VmRunWrapper.SharedFolderSetAccess Method (VMWareVirtualMachine, VmSharedFolderInfo, Boolean)
 

Sets the writable/readonly access of a shared folder in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SharedFolderSetAccess(
	VMWareVirtualMachine vm,
	VmSharedFolderInfo sharedFolder,
	bool allowWriteAccess
)
```

**VB**<br />
``` VB
Public Sub SharedFolderSetAccess ( 
	vm As VMWareVirtualMachine,
	sharedFolder As VmSharedFolderInfo,
	allowWriteAccess As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim sharedFolder As VmSharedFolderInfo
Dim allowWriteAccess As Boolean

instance.SharedFolderSetAccess(vm, sharedFolder, 
	allowWriteAccess)
```

**C++**<br />
``` C++
public:
void SharedFolderSetAccess(
	VMWareVirtualMachine^ vm, 
	VmSharedFolderInfo^ sharedFolder, 
	bool allowWriteAccess
)
```

**F#**<br />
``` F#
member SharedFolderSetAccess : 
        vm : VMWareVirtualMachine * 
        sharedFolder : VmSharedFolderInfo * 
        allowWriteAccess : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>sharedFolder</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VmSharedFolderInfo">DevCase.ThirdParty.VmWare.VmSharedFolderInfo</a><br />The shared folder.</dd><dt>allowWriteAccess</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), allow write access to the shared folder; otherwise, make the shared folder read-only.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderSetAccess">SharedFolderSetAccess Overload</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />