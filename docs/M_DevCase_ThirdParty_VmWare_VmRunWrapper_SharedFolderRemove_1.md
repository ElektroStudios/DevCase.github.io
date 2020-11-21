# VmRunWrapper.SharedFolderRemove Method (VMWareVirtualMachine, String)
 

Adds a new shared folder in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SharedFolderRemove(
	VMWareVirtualMachine vm,
	string shareName
)
```

**VB**<br />
``` VB
Public Sub SharedFolderRemove ( 
	vm As VMWareVirtualMachine,
	shareName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim shareName As String

instance.SharedFolderRemove(vm, shareName)
```

**C++**<br />
``` C++
public:
void SharedFolderRemove(
	VMWareVirtualMachine^ vm, 
	String^ shareName
)
```

**F#**<br />
``` F#
member SharedFolderRemove : 
        vm : VMWareVirtualMachine * 
        shareName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>shareName</dt><dd>Type: System.String<br />The name of the shared folder being removed.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_VmWare_VmRunWrapper_SharedFolderRemove">SharedFolderRemove Overload</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />