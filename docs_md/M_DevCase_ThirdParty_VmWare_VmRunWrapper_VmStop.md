# VmRunWrapper.VmStop Method 
 

Stop the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void VmStop(
	VMWareVirtualMachine vm,
	bool hardStop
)
```

**VB**<br />
``` VB
Public Sub VmStop ( 
	vm As VMWareVirtualMachine,
	hardStop As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim hardStop As Boolean

instance.VmStop(vm, hardStop)
```

**C++**<br />
``` C++
public:
void VmStop(
	VMWareVirtualMachine^ vm, 
	bool hardStop
)
```

**F#**<br />
``` F#
member VmStop : 
        vm : VMWareVirtualMachine * 
        hardStop : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>hardStop</dt><dd>Type: System.Boolean<br />A value indicating whether to perform a hard or soft stop.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />