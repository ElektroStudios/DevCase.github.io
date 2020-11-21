# VmRunWrapper.FileCopyFromGuestToHost Method 
 

Copies a file from the guest operating system of the specified virtual machine to the host operating system.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void FileCopyFromGuestToHost(
	VMWareVirtualMachine vm,
	string guestFilePath,
	string hostFilePath
)
```

**VB**<br />
``` VB
Public Sub FileCopyFromGuestToHost ( 
	vm As VMWareVirtualMachine,
	guestFilePath As String,
	hostFilePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim guestFilePath As String
Dim hostFilePath As String

instance.FileCopyFromGuestToHost(vm, 
	guestFilePath, hostFilePath)
```

**C++**<br />
``` C++
public:
void FileCopyFromGuestToHost(
	VMWareVirtualMachine^ vm, 
	String^ guestFilePath, 
	String^ hostFilePath
)
```

**F#**<br />
``` F#
member FileCopyFromGuestToHost : 
        vm : VMWareVirtualMachine * 
        guestFilePath : string * 
        hostFilePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>guestFilePath</dt><dd>Type: System.String<br />The source file path; the file to be copied from the guest operating system.</dd><dt>hostFilePath</dt><dd>Type: System.String<br />The destination file path; the file being copied into the host operating system.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />