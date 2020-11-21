# SecurityAttributes.InheritHandle Field
 

A value that specifies whether the returned handle is inherited when a new process is created. 

 If this member is `true` (`True` in Visual Basic), the new process inherits the handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool InheritHandle
```

**VB**<br />
``` VB
Public InheritHandle As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SecurityAttributes
Dim value As Boolean

value = instance.InheritHandle

instance.InheritHandle = value
```

**C++**<br />
``` C++
public:
bool InheritHandle
```

**F#**<br />
``` F#
val mutable InheritHandle: bool
```


#### Field Value
Type: Boolean

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />