# ProcessUtil.SetProcessSecurityDescriptor Method (IntPtr, RawSecurityDescriptor)
 

Sets the security descriptor of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetProcessSecurityDescriptor(
	IntPtr processHandle,
	RawSecurityDescriptor dacl
)
```

**VB**<br />
``` VB
Public Shared Sub SetProcessSecurityDescriptor ( 
	processHandle As IntPtr,
	dacl As RawSecurityDescriptor
)
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim dacl As RawSecurityDescriptorProcessUtil.SetProcessSecurityDescriptor(processHandle, 
	dacl)
```

**C++**<br />
``` C++
public:
static void SetProcessSecurityDescriptor(
	IntPtr processHandle, 
	RawSecurityDescriptor^ dacl
)
```

**F#**<br />
``` F#
static member SetProcessSecurityDescriptor : 
        processHandle : IntPtr * 
        dacl : RawSecurityDescriptor -> unit 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />The process handle.</dd><dt>dacl</dt><dd>Type: System.Security.AccessControl.RawSecurityDescriptor<br />The security descriptor.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
' Read the process DACL.
Dim processHandle As IntPtr = Process.GetCurrentProcess().Handle
Dim dacl As RawSecurityDescriptor = GetProcessSecurityDescriptor(processHandle)

' Insert the new ACE.
Dim ace As New CommonAce(AceFlags.None, AceQualifier.AccessDenied, DevCase.Interop.Unmanaged.Win32.ProcessAccessRights.AllAccess, New SecurityIdentifier(WellKnownSidType.WorldSid, Nothing), False, Nothing)
dacl.DiscretionaryAcl.InsertAce(0, ace)

' Save the process DACL.
SetProcessSecurityDescriptor(processHandle, dacl)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessSecurityDescriptor">SetProcessSecurityDescriptor Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />