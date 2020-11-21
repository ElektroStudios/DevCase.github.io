# VmRunWrapper.FileDelete Method 
 

Delete a file from the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void FileDelete(
	VMWareVirtualMachine vm,
	string filepath
)
```

**VB**<br />
``` VB
Public Sub FileDelete ( 
	vm As VMWareVirtualMachine,
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim filepath As String

instance.FileDelete(vm, filepath)
```

**C++**<br />
``` C++
public:
void FileDelete(
	VMWareVirtualMachine^ vm, 
	String^ filepath
)
```

**F#**<br />
``` F#
member FileDelete : 
        vm : VMWareVirtualMachine * 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>filepath</dt><dd>Type: System.String<br />The full path of the file to be deleted in the guest operating system.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />