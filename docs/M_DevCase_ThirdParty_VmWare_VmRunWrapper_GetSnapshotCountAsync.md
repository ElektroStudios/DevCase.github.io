# VmRunWrapper.GetSnapshotCountAsync Method 
 

Asynchronously gets the amount of snapshots created in the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<int> GetSnapshotCountAsync(
	VMWareVirtualMachine vm
)
```

**VB**<br />
``` VB
Public Function GetSnapshotCountAsync ( 
	vm As VMWareVirtualMachine
) As Task(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim returnValue As Task(Of Integer)

returnValue = instance.GetSnapshotCountAsync(vm)
```

**C++**<br />
``` C++
public:
Task<int>^ GetSnapshotCountAsync(
	VMWareVirtualMachine^ vm
)
```

**F#**<br />
``` F#
member GetSnapshotCountAsync : 
        vm : VMWareVirtualMachine -> Task<int> 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd></dl>

#### Return Value
Type: Task(Int32)<br />The amount of snapshots created.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />