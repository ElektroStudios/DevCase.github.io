# ProcessUtil.SetProcessSecurityDescriptor Method (Int32, RawSecurityDescriptor)
 

Sets the security descriptor of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetProcessSecurityDescriptor(
	int processId,
	RawSecurityDescriptor dacl
)
```

**VB**<br />
``` VB
Public Shared Sub SetProcessSecurityDescriptor ( 
	processId As Integer,
	dacl As RawSecurityDescriptor
)
```

**VB Usage**<br />
``` VB Usage
Dim processId As Integer
Dim dacl As RawSecurityDescriptorProcessUtil.SetProcessSecurityDescriptor(processId, 
	dacl)
```

**C++**<br />
``` C++
public:
static void SetProcessSecurityDescriptor(
	int processId, 
	RawSecurityDescriptor^ dacl
)
```

**F#**<br />
``` F#
static member SetProcessSecurityDescriptor : 
        processId : int * 
        dacl : RawSecurityDescriptor -> unit 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.Int32<br />The process identifier.</dd><dt>dacl</dt><dd>Type: System.Security.AccessControl.RawSecurityDescriptor<br />The security descriptor.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
' Read the process DACL.
Dim processId As Integer = Process.GetCurrentProcess().Id
Dim dacl As RawSecurityDescriptor = GetProcessSecurityDescriptor(processId)

' Insert the new ACE.
Dim ace As New CommonAce(AceFlags.None, AceQualifier.AccessDenied, DevCase.Interop.Unmanaged.Win32.ProcessAccessRights.AllAccess, New SecurityIdentifier(WellKnownSidType.WorldSid, Nothing), False, Nothing)
dacl.DiscretionaryAcl.InsertAce(0, ace)

' Save the process DACL.
SetProcessSecurityDescriptor(processId, dacl)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessSecurityDescriptor">SetProcessSecurityDescriptor Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />