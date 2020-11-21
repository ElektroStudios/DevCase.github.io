# VmRunWrapper.CaptureScreen Method 
 

Capture the screen of the guest operating system of the specified virtual machine and save it to a image file (in .PNG format) in the host operating system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void CaptureScreen(
	VMWareVirtualMachine vm,
	string hostFilePath
)
```

**VB**<br />
``` VB
Public Sub CaptureScreen ( 
	vm As VMWareVirtualMachine,
	hostFilePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim hostFilePath As String

instance.CaptureScreen(vm, hostFilePath)
```

**C++**<br />
``` C++
public:
void CaptureScreen(
	VMWareVirtualMachine^ vm, 
	String^ hostFilePath
)
```

**F#**<br />
``` F#
member CaptureScreen : 
        vm : VMWareVirtualMachine * 
        hostFilePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>hostFilePath</dt><dd>Type: System.String<br />The full path to the image file that will be created in the host operating system.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />