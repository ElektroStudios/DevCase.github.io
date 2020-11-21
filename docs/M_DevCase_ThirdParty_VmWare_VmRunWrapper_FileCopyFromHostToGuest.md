# VmRunWrapper.FileCopyFromHostToGuest Method 
 

Copies a file from the host operating system to the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void FileCopyFromHostToGuest(
	VMWareVirtualMachine vm,
	string hostFilePath,
	string guestFilePath
)
```

**VB**<br />
``` VB
Public Sub FileCopyFromHostToGuest ( 
	vm As VMWareVirtualMachine,
	hostFilePath As String,
	guestFilePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim hostFilePath As String
Dim guestFilePath As String

instance.FileCopyFromHostToGuest(vm, 
	hostFilePath, guestFilePath)
```

**C++**<br />
``` C++
public:
void FileCopyFromHostToGuest(
	VMWareVirtualMachine^ vm, 
	String^ hostFilePath, 
	String^ guestFilePath
)
```

**F#**<br />
``` F#
member FileCopyFromHostToGuest : 
        vm : VMWareVirtualMachine * 
        hostFilePath : string * 
        guestFilePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>hostFilePath</dt><dd>Type: System.String<br />The source file path; the file to be copied from the host operating system.</dd><dt>guestFilePath</dt><dd>Type: System.String<br />The destination file path; the file being copied into the guest operating system.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />