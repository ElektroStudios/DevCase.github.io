# VMWareVirtualMachine.ProcessorCount Property 
 

Gets the amount of processors of this VM. 

 The resulting value is the division between <a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_TotalProcessorCores">TotalProcessorCores</a> \ <a href="P_DevCase_ThirdParty_VmWare_VMWareVirtualMachine_CoresPerProcessor">CoresPerProcessor</a>.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ProcessorCount { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ProcessorCount As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As VMWareVirtualMachine
Dim value As Integer

value = instance.ProcessorCount

```

**C++**<br />
``` C++
public:
property int ProcessorCount {
	int get ();
}
```

**F#**<br />
``` F#
member ProcessorCount : int with get

```


#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.VmWare.VMWareVirtualMachine.ProcessorCount"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />