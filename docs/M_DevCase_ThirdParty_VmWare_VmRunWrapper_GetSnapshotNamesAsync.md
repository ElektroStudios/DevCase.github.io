# VmRunWrapper.GetSnapshotNamesAsync Method 
 

Asynchronously gets the names of the snapshots created in the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<ReadOnlyCollection<string>> GetSnapshotNamesAsync(
	VMWareVirtualMachine vm
)
```

**VB**<br />
``` VB
Public Function GetSnapshotNamesAsync ( 
	vm As VMWareVirtualMachine
) As Task(Of ReadOnlyCollection(Of String))
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim returnValue As Task(Of ReadOnlyCollection(Of String))

returnValue = instance.GetSnapshotNamesAsync(vm)
```

**C++**<br />
``` C++
public:
Task<ReadOnlyCollection<String^>^>^ GetSnapshotNamesAsync(
	VMWareVirtualMachine^ vm
)
```

**F#**<br />
``` F#
member GetSnapshotNamesAsync : 
        vm : VMWareVirtualMachine -> Task<ReadOnlyCollection<string>> 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd></dl>

#### Return Value
Type: Task(ReadOnlyCollection(String))<br />The snapshot names.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />