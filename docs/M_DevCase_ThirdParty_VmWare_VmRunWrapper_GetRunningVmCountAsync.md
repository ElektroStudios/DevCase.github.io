# VmRunWrapper.GetRunningVmCountAsync Method 
 

Asynchronously gets the amount of virtual machines that are running on the host operating system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<int> GetRunningVmCountAsync()
```

**VB**<br />
``` VB
Public Function GetRunningVmCountAsync As Task(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim returnValue As Task(Of Integer)

returnValue = instance.GetRunningVmCountAsync()
```

**C++**<br />
``` C++
public:
Task<int>^ GetRunningVmCountAsync()
```

**F#**<br />
``` F#
member GetRunningVmCountAsync : unit -> Task<int> 

```


#### Return Value
Type: Task(Int32)<br />The amount of virtual machines that are running on the host operating system.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />