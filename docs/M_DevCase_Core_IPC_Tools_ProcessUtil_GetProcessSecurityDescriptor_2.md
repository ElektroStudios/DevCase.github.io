# ProcessUtil.GetProcessSecurityDescriptor Method (IntPtr)
 

Gets the security descriptor of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RawSecurityDescriptor GetProcessSecurityDescriptor(
	IntPtr processHandle
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessSecurityDescriptor ( 
	processHandle As IntPtr
) As RawSecurityDescriptor
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim returnValue As RawSecurityDescriptor

returnValue = ProcessUtil.GetProcessSecurityDescriptor(processHandle)
```

**C++**<br />
``` C++
public:
static RawSecurityDescriptor^ GetProcessSecurityDescriptor(
	IntPtr processHandle
)
```

**F#**<br />
``` F#
static member GetProcessSecurityDescriptor : 
        processHandle : IntPtr -> RawSecurityDescriptor 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />The process handle.</dd></dl>

#### Return Value
Type: RawSecurityDescriptor<br />The resulting RawSecurityDescriptor.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim processHandle As IntPtr = Process.GetCurrentProcess().Handle
Dim dacl As RawSecurityDescriptor = GetProcessSecurityDescriptor(processHandle)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessSecurityDescriptor">GetProcessSecurityDescriptor Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />