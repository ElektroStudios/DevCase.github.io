# VmRunWrapper.FileExists Method 
 

Determine whether a file exists in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool FileExists(
	VMWareVirtualMachine vm,
	string filepath
)
```

**VB**<br />
``` VB
Public Function FileExists ( 
	vm As VMWareVirtualMachine,
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim filepath As String
Dim returnValue As Boolean

returnValue = instance.FileExists(vm, 
	filepath)
```

**C++**<br />
``` C++
public:
bool FileExists(
	VMWareVirtualMachine^ vm, 
	String^ filepath
)
```

**F#**<br />
``` F#
member FileExists : 
        vm : VMWareVirtualMachine * 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>filepath</dt><dd>Type: System.String<br />The full path to a existing file in the guest operating system.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the file exists in the guest operating system; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />