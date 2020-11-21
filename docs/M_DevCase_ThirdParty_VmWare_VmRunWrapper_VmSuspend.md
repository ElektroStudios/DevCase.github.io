# VmRunWrapper.VmSuspend Method 
 

Suspend the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void VmSuspend(
	VMWareVirtualMachine vm,
	bool hardSuspend
)
```

**VB**<br />
``` VB
Public Sub VmSuspend ( 
	vm As VMWareVirtualMachine,
	hardSuspend As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim hardSuspend As Boolean

instance.VmSuspend(vm, hardSuspend)
```

**C++**<br />
``` C++
public:
void VmSuspend(
	VMWareVirtualMachine^ vm, 
	bool hardSuspend
)
```

**F#**<br />
``` F#
member VmSuspend : 
        vm : VMWareVirtualMachine * 
        hardSuspend : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>hardSuspend</dt><dd>Type: System.Boolean<br />A value indicating whether to perform a hard or soft suspend.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />