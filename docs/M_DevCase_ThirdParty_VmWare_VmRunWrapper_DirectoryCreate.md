# VmRunWrapper.DirectoryCreate Method 
 

Create a directory in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void DirectoryCreate(
	VMWareVirtualMachine vm,
	string directoryPath
)
```

**VB**<br />
``` VB
Public Sub DirectoryCreate ( 
	vm As VMWareVirtualMachine,
	directoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim directoryPath As String

instance.DirectoryCreate(vm, directoryPath)
```

**C++**<br />
``` C++
public:
void DirectoryCreate(
	VMWareVirtualMachine^ vm, 
	String^ directoryPath
)
```

**F#**<br />
``` F#
member DirectoryCreate : 
        vm : VMWareVirtualMachine * 
        directoryPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>directoryPath</dt><dd>Type: System.String<br />The full path of the directory to be created in the guest operating system.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />