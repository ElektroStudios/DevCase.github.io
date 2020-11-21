# VmRunWrapper.GetSnapshotsTreeview Method 
 

Gets a tree-view of the snapshots created in the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string GetSnapshotsTreeview(
	VMWareVirtualMachine vm
)
```

**VB**<br />
``` VB
Public Function GetSnapshotsTreeview ( 
	vm As VMWareVirtualMachine
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim returnValue As String

returnValue = instance.GetSnapshotsTreeview(vm)
```

**C++**<br />
``` C++
public:
String^ GetSnapshotsTreeview(
	VMWareVirtualMachine^ vm
)
```

**F#**<br />
``` F#
member GetSnapshotsTreeview : 
        vm : VMWareVirtualMachine -> string 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd></dl>

#### Return Value
Type: String<br />A tree-view of the snapshots.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />