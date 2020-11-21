# VmRunWrapper.IsVmWareToolsInstalledAsync Method 
 

Asynchronously gets a value that determine whether VmWare Tools is installed in the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<bool> IsVmWareToolsInstalledAsync(
	VMWareVirtualMachine vm
)
```

**VB**<br />
``` VB
Public Function IsVmWareToolsInstalledAsync ( 
	vm As VMWareVirtualMachine
) As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim returnValue As Task(Of Boolean)

returnValue = instance.IsVmWareToolsInstalledAsync(vm)
```

**C++**<br />
``` C++
public:
Task<bool>^ IsVmWareToolsInstalledAsync(
	VMWareVirtualMachine^ vm
)
```

**F#**<br />
``` F#
member IsVmWareToolsInstalledAsync : 
        vm : VMWareVirtualMachine -> Task<bool> 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd></dl>

#### Return Value
Type: Task(Boolean)<br />`true` (`True` in Visual Basic) if VmWare Tools is installed in the specified virtual machine; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />