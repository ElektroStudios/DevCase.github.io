# VmRunWrapper.ProcessRunScriptAsync Method 
 

Asynchronously runs a script in the guest operating system of the specified virtual machine.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> ProcessRunScriptAsync(
	VMWareVirtualMachine vm,
	string interpreterPath,
	VmRunProgramFlags flags,
	string scriptContent
)
```

**VB**<br />
``` VB
Public Function ProcessRunScriptAsync ( 
	vm As VMWareVirtualMachine,
	interpreterPath As String,
	flags As VmRunProgramFlags,
	scriptContent As String
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunWrapper
Dim vm As VMWareVirtualMachine
Dim interpreterPath As String
Dim flags As VmRunProgramFlags
Dim scriptContent As String
Dim returnValue As Task(Of String)

returnValue = instance.ProcessRunScriptAsync(vm, 
	interpreterPath, flags, scriptContent)
```

**C++**<br />
``` C++
public:
Task<String^>^ ProcessRunScriptAsync(
	VMWareVirtualMachine^ vm, 
	String^ interpreterPath, 
	VmRunProgramFlags flags, 
	String^ scriptContent
)
```

**F#**<br />
``` F#
member ProcessRunScriptAsync : 
        vm : VMWareVirtualMachine * 
        interpreterPath : string * 
        flags : VmRunProgramFlags * 
        scriptContent : string -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>vm</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VMWareVirtualMachine">DevCase.ThirdParty.VmWare.VMWareVirtualMachine</a><br />The VMWare virtual machine.</dd><dt>interpreterPath</dt><dd>Type: System.String<br />The full path to the interpreter executable file in the guest operating system. (eg. "C:\Windows\System32\cscript.exe")</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_ThirdParty_VmWare_VmRunProgramFlags">DevCase.ThirdParty.VmWare.VmRunProgramFlags</a><br />Flags that determine the runtime behavior. You can combine the flags.</dd><dt>scriptContent</dt><dd>Type: System.String<br />The text content of the script to run.</dd></dl>

#### Return Value
Type: Task(String)<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.VmWare.VmRunWrapper.ProcessRunScriptAsync(DevCase.ThirdParty.VmWare.VMWareVirtualMachine,System.String,DevCase.ThirdParty.VmWare.VmRunProgramFlags,System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_VmRunWrapper">VmRunWrapper Class</a><br /><a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />