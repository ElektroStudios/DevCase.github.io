# ProcessUtil.GetProcessSecurityDescriptor Method (Process)
 

Gets the security descriptor of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RawSecurityDescriptor GetProcessSecurityDescriptor(
	Process process
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessSecurityDescriptor ( 
	process As Process
) As RawSecurityDescriptor
```

**VB Usage**<br />
``` VB Usage
Dim process As Process
Dim returnValue As RawSecurityDescriptor

returnValue = ProcessUtil.GetProcessSecurityDescriptor(process)
```

**C++**<br />
``` C++
public:
static RawSecurityDescriptor^ GetProcessSecurityDescriptor(
	Process^ process
)
```

**F#**<br />
``` F#
static member GetProcessSecurityDescriptor : 
        process : Process -> RawSecurityDescriptor 

```


#### Parameters
&nbsp;<dl><dt>process</dt><dd>Type: System.Diagnostics.Process<br />The Process.</dd></dl>

#### Return Value
Type: RawSecurityDescriptor<br />The resulting RawSecurityDescriptor.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim process As Process = Process.GetCurrentProcess()
Dim dacl As RawSecurityDescriptor = GetProcessSecurityDescriptor(process)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessSecurityDescriptor">GetProcessSecurityDescriptor Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />