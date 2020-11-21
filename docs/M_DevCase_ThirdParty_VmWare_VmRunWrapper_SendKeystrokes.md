# VmRunWrapper.SendKeystrokes Method 
 

Send keystrokes to the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SendKeystrokes(
	VMWareVirtualMachine vm,
	string keystrokes
)
```

**VB**<br />
``` VB
Public Sub SendKeystrokes ( 
	vm As VMWareVirtualMachine,
	keystrokes As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim keystrokes As String

instance.SendKeystrokes(vm, keystrokes)
```

**C++**<br />
``` C++
public:
void SendKeystrokes(
	VMWareVirtualMachine^ vm, 
	String^ keystrokes
)
```

**F#**<br />
``` F#
member SendKeystrokes : 
        vm : VMWareVirtualMachine * 
        keystrokes : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>keystrokes</dt><dd>Type: System.String<br />The keystrokes to send.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />