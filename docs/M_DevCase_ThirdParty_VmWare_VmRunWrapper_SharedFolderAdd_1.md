# VmRunWrapper.SharedFolderAdd Method (VMWareVirtualMachine, String, String)
 

Adds a new shared folder in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SharedFolderAdd(
	VMWareVirtualMachine vm,
	string shareName,
	string hostDirectoryPath
)
```

**VB**<br />
``` VB
Public Sub SharedFolderAdd ( 
	vm As VMWareVirtualMachine,
	shareName As String,
	hostDirectoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim shareName As String
Dim hostDirectoryPath As String

instance.SharedFolderAdd(vm, shareName, 
	hostDirectoryPath)
```

**C++**<br />
``` C++
public:
void SharedFolderAdd(
	VMWareVirtualMachine^ vm, 
	String^ shareName, 
	String^ hostDirectoryPath
)
```

**F#**<br />
``` F#
member SharedFolderAdd : 
        vm : VMWareVirtualMachine * 
        shareName : string * 
        hostDirectoryPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>shareName</dt><dd>Type: System.String<br />The name to assign to the shared folder.</dd><dt>hostDirectoryPath</dt><dd>Type: System.String<br />The full path to the directory on the host operating system being shared.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderAdd">SharedFolderAdd Overload</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />