# ProcessUtil.GetProcessSecurityDescriptor Method (Int32)
 

Gets the security descriptor of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RawSecurityDescriptor GetProcessSecurityDescriptor(
	int processId
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessSecurityDescriptor ( 
	processId As Integer
) As RawSecurityDescriptor
```

**VB Usage**<br />
``` VB Usage
Dim processId As Integer
Dim returnValue As RawSecurityDescriptor

returnValue = ProcessUtil.GetProcessSecurityDescriptor(processId)
```

**C++**<br />
``` C++
public:
static RawSecurityDescriptor^ GetProcessSecurityDescriptor(
	int processId
)
```

**F#**<br />
``` F#
static member GetProcessSecurityDescriptor : 
        processId : int -> RawSecurityDescriptor 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.Int32<br />The process identifier (PID).</dd></dl>

#### Return Value
Type: RawSecurityDescriptor<br />The resulting RawSecurityDescriptor.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pid As Integer = Process.GetCurrentProcess().Id
Dim dacl As RawSecurityDescriptor = GetProcessSecurityDescriptor(pid)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessSecurityDescriptor">GetProcessSecurityDescriptor Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />