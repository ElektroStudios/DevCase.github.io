# MutexOwnerInformation Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MutexOwnerInformation">MutexOwnerInformation</a> struct.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MutexOwnerInformation(
	int processId,
	int threadId
)
```

**VB**<br />
``` VB
Public Sub New ( 
	processId As Integer,
	threadId As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim processId As Integer
Dim threadId As Integer

Dim instance As New MutexOwnerInformation(processId, 
	threadId)
```

**C++**<br />
``` C++
public:
MutexOwnerInformation(
	int processId, 
	int threadId
)
```

**F#**<br />
``` F#
new : 
        processId : int * 
        threadId : int -> MutexOwnerInformation
```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.Int32<br />The identifier of the process that owns the mutex.</dd><dt>threadId</dt><dd>Type: System.Int32<br />The identifier of the thread that owns the mutex.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MutexOwnerInformation">MutexOwnerInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />