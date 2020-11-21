# VmRunWrapper.GetRunningVmsAsync Method 
 

Asynchronously gets the file paths of the virtual machines that are running on the host operating system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<ReadOnlyCollection<VMWareVirtualMachine>> GetRunningVmsAsync()
```

**VB**<br />
``` VB
Public Function GetRunningVmsAsync As Task(Of ReadOnlyCollection(Of VMWareVirtualMachine))
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim returnValue As Task(Of ReadOnlyCollection(Of VMWareVirtualMachine))

returnValue = instance.GetRunningVmsAsync()
```

**C++**<br />
``` C++
public:
Task<ReadOnlyCollection<VMWareVirtualMachine^>^>^ GetRunningVmsAsync()
```

**F#**<br />
``` F#
member GetRunningVmsAsync : unit -> Task<ReadOnlyCollection<VMWareVirtualMachine>> 

```


#### Return Value
Type: Task(ReadOnlyCollection(<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine</a>))<br />The file paths of the virtual machines that are running on the host operating system.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />