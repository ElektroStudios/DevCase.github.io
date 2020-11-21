# Win32FindDataW.LastWriteTime Field
 

A FILETIME structure. 

 For a file, the structure specifies when the file was last written to, truncated, or overwritten, for example, when WriteFile or SetEndOfFile are used. 

 The date and time are not updated when file attributes or security descriptors are changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long LastWriteTime
```

**VB**<br />
``` VB
Public LastWriteTime As Long
```

**VB Usage**<br />
``` VB Usage
Dim instance As Win32FindDataW
Dim value As Long

value = instance.LastWriteTime

instance.LastWriteTime = value
```

**C++**<br />
``` C++
public:
long long LastWriteTime
```

**F#**<br />
``` F#
val mutable LastWriteTime: int64
```


#### Field Value
Type: Int64

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />