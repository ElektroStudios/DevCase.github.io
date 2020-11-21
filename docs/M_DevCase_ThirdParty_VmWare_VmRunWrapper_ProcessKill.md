# VmRunWrapper.ProcessKill Method 
 

Kills a running process from the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void ProcessKill(
	VMWareVirtualMachine vm,
	int pid
)
```

**VB**<br />
``` VB
Public Sub ProcessKill ( 
	vm As VMWareVirtualMachine,
	pid As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim pid As Integer

instance.ProcessKill(vm, pid)
```

**C++**<br />
``` C++
public:
void ProcessKill(
	VMWareVirtualMachine^ vm, 
	int pid
)
```

**F#**<br />
``` F#
member ProcessKill : 
        vm : VMWareVirtualMachine * 
        pid : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>pid</dt><dd>Type: System.Int32<br />The process identifier.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />