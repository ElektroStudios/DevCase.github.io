# VmRunWrapper.ProcessRun Method 
 

Runs a new process in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void ProcessRun(
	VMWareVirtualMachine vm,
	string executablePath,
	VmRunProgramFlags flags,
	string arguments = ""
)
```

**VB**<br />
``` VB
Public Sub ProcessRun ( 
	vm As VMWareVirtualMachine,
	executablePath As String,
	flags As VmRunProgramFlags,
	Optional arguments As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim executablePath As String
Dim flags As VmRunProgramFlags
Dim arguments As String

instance.ProcessRun(vm, executablePath, 
	flags, arguments)
```

**C++**<br />
``` C++
public:
void ProcessRun(
	VMWareVirtualMachine^ vm, 
	String^ executablePath, 
	VmRunProgramFlags flags, 
	String^ arguments = L""
)
```

**F#**<br />
``` F#
member ProcessRun : 
        vm : VMWareVirtualMachine * 
        executablePath : string * 
        flags : VmRunProgramFlags * 
        ?arguments : string 
(* Defaults:
        let _arguments = defaultArg arguments ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>executablePath</dt><dd>Type: System.String<br />The full path to the executable file in the guest operating system.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VmRunProgramFlags">DevCase.ThirdParty.VmWare.VmRunProgramFlags</a><br />Flags that determine the runtime behavior. You can combine the flags.</dd><dt>arguments (Optional)</dt><dd>Type: System.String<br />The program arguments.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />