# VmRunWrapper.GetSnapshotsTreeviewAsync Method 
 

Asynchronously gets a tree-view of the snapshots created in the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> GetSnapshotsTreeviewAsync(
	VMWareVirtualMachine vm
)
```

**VB**<br />
``` VB
Public Function GetSnapshotsTreeviewAsync ( 
	vm As VMWareVirtualMachine
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim returnValue As Task(Of String)

returnValue = instance.GetSnapshotsTreeviewAsync(vm)
```

**C++**<br />
``` C++
public:
Task<String^>^ GetSnapshotsTreeviewAsync(
	VMWareVirtualMachine^ vm
)
```

**F#**<br />
``` F#
member GetSnapshotsTreeviewAsync : 
        vm : VMWareVirtualMachine -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd></dl>

#### Return Value
Type: Task(String)<br />A tree-view of the snapshots.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />