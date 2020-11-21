# VmRunWrapper.DirectoryExistsAsync Method 
 

Asynchronously determine whether a directory exists in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<bool> DirectoryExistsAsync(
	VMWareVirtualMachine vm,
	string directoryPath
)
```

**VB**<br />
``` VB
Public Function DirectoryExistsAsync ( 
	vm As VMWareVirtualMachine,
	directoryPath As String
) As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim directoryPath As String
Dim returnValue As Task(Of Boolean)

returnValue = instance.DirectoryExistsAsync(vm, 
	directoryPath)
```

**C++**<br />
``` C++
public:
Task<bool>^ DirectoryExistsAsync(
	VMWareVirtualMachine^ vm, 
	String^ directoryPath
)
```

**F#**<br />
``` F#
member DirectoryExistsAsync : 
        vm : VMWareVirtualMachine * 
        directoryPath : string -> Task<bool> 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>directoryPath</dt><dd>Type: System.String<br />The full path to a existing file in the guest operating system.</dd></dl>

#### Return Value
Type: Task(Boolean)<br />`true` (`True` in Visual Basic) if the directory exists in the guest operating system; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />