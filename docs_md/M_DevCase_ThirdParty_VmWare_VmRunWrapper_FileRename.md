# VmRunWrapper.FileRename Method 
 

Rename a file in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void FileRename(
	VMWareVirtualMachine vm,
	string srcFilepath,
	string dstFilepath
)
```

**VB**<br />
``` VB
Public Sub FileRename ( 
	vm As VMWareVirtualMachine,
	srcFilepath As String,
	dstFilepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim srcFilepath As String
Dim dstFilepath As String

instance.FileRename(vm, srcFilepath, dstFilepath)
```

**C++**<br />
``` C++
public:
void FileRename(
	VMWareVirtualMachine^ vm, 
	String^ srcFilepath, 
	String^ dstFilepath
)
```

**F#**<br />
``` F#
member FileRename : 
        vm : VMWareVirtualMachine * 
        srcFilepath : string * 
        dstFilepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>srcFilepath</dt><dd>Type: System.String<br />The full path to a existing file in the guest operating system.</dd><dt>dstFilepath</dt><dd>Type: System.String<br />The new destination path for the file set in the *srcFilepath* parameter.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />