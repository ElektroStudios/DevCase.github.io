# Win32FindDataW.CreationTime Field
 

A FILETIME structure that specifies when a file or directory was created. If the underlying file system does not support creation time, this member is zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long CreationTime
```

**VB**<br />
``` VB
Public CreationTime As Long
```

**VB Usage**<br />
``` VB Usage
Dim instance As Win32FindDataW
Dim value As Long

value = instance.CreationTime

instance.CreationTime = value
```

**C++**<br />
``` C++
public:
long long CreationTime
```

**F#**<br />
``` F#
val mutable CreationTime: int64
```


#### Field Value
Type: Int64

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />