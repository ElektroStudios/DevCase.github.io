# VmRunWrapper.GetIpAddress Method 
 

Gets the IP address of the guest operating system on the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IPAddress GetIpAddress(
	VMWareVirtualMachine vm
)
```

**VB**<br />
``` VB
Public Function GetIpAddress ( 
	vm As VMWareVirtualMachine
) As IPAddress
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim returnValue As IPAddress

returnValue = instance.GetIpAddress(vm)
```

**C++**<br />
``` C++
public:
IPAddress^ GetIpAddress(
	VMWareVirtualMachine^ vm
)
```

**F#**<br />
``` F#
member GetIpAddress : 
        vm : VMWareVirtualMachine -> IPAddress 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd></dl>

#### Return Value
Type: IPAddress<br />The resulting IPAddress.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />