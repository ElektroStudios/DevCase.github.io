# VmRunWrapper.GetRunningVms Method 
 

Gets the file paths of the virtual machines that are running on the host operating system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<VMWareVirtualMachine> GetRunningVms()
```

**VB**<br />
``` VB
Public Function GetRunningVms As ReadOnlyCollection(Of VMWareVirtualMachine)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim returnValue As ReadOnlyCollection(Of VMWareVirtualMachine)

returnValue = instance.GetRunningVms()
```

**C++**<br />
``` C++
public:
ReadOnlyCollection<VMWareVirtualMachine^>^ GetRunningVms()
```

**F#**<br />
``` F#
member GetRunningVms : unit -> ReadOnlyCollection<VMWareVirtualMachine> 

```


#### Return Value
Type: ReadOnlyCollection(<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine</a>)<br />The file paths of the virtual machines that are running on the host operating system.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />