# VmRunWrapper.SnapshotCreate Method 
 

Create a snapshot of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SnapshotCreate(
	VMWareVirtualMachine vm,
	string name
)
```

**VB**<br />
``` VB
Public Sub SnapshotCreate ( 
	vm As VMWareVirtualMachine,
	name As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim name As String

instance.SnapshotCreate(vm, name)
```

**C++**<br />
``` C++
public:
void SnapshotCreate(
	VMWareVirtualMachine^ vm, 
	String^ name
)
```

**F#**<br />
``` F#
member SnapshotCreate : 
        vm : VMWareVirtualMachine * 
        name : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>name</dt><dd>Type: System.String<br />The snapshot name.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />