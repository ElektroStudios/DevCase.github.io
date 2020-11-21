# VMWareVirtualMachine Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public VMWareVirtualMachine(
	string vmxFilePath,
	bool isSharedVm
)
```

**VB**<br />
``` VB
Public Sub New ( 
	vmxFilePath As String,
	isSharedVm As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim vmxFilePath As String
Dim isSharedVm As Boolean

Dim instance As New VMWareVirtualMachine(vmxFilePath, 
	isSharedVm)
```

**C++**<br />
``` C++
public:
VMWareVirtualMachine(
	String^ vmxFilePath, 
	bool isSharedVm
)
```

**F#**<br />
``` F#
new : 
        vmxFilePath : string * 
        isSharedVm : bool -> VMWareVirtualMachine
```


#### Parameters
&nbsp;<dl><dt>vmxFilePath</dt><dd>Type: System.String<br />The full path to the .vmx file.</dd><dt>isSharedVm</dt><dd>Type: System.Boolean<br />A value that determine whether the VM is a shared VM.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">VMWareVirtualMachine Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />