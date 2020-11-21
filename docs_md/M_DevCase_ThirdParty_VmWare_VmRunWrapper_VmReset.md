# VmRunWrapper.VmReset Method 
 

Reset the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void VmReset(
	VMWareVirtualMachine vm,
	bool hardReset
)
```

**VB**<br />
``` VB
Public Sub VmReset ( 
	vm As VMWareVirtualMachine,
	hardReset As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim hardReset As Boolean

instance.VmReset(vm, hardReset)
```

**C++**<br />
``` C++
public:
void VmReset(
	VMWareVirtualMachine^ vm, 
	bool hardReset
)
```

**F#**<br />
``` F#
member VmReset : 
        vm : VMWareVirtualMachine * 
        hardReset : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>hardReset</dt><dd>Type: System.Boolean<br />A value indicating whether to perform a hard or soft reset.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />