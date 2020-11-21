# VmRunWrapper.VmStart Method 
 

Start the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void VmStart(
	VMWareVirtualMachine vm,
	bool noGui
)
```

**VB**<br />
``` VB
Public Sub VmStart ( 
	vm As VMWareVirtualMachine,
	noGui As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim noGui As Boolean

instance.VmStart(vm, noGui)
```

**C++**<br />
``` C++
public:
void VmStart(
	VMWareVirtualMachine^ vm, 
	bool noGui
)
```

**F#**<br />
``` F#
member VmStart : 
        vm : VMWareVirtualMachine * 
        noGui : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>noGui</dt><dd>Type: System.Boolean<br />A value indicating whether to start the virtual machine with VmWare GUI or not.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />