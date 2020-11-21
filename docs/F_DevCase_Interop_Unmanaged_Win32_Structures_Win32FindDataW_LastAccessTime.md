# Win32FindDataW.LastAccessTime Field
 

A FILETIME structure. 

 For a file, the structure specifies when the file was last read from, written to, or for executable files, run. 

 For a directory, the structure specifies when the directory is created. 

 If the underlying file system does not support last access time, this member is zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long LastAccessTime
```

**VB**<br />
``` VB
Public LastAccessTime As Long
```

**VB Usage**<br />
``` VB Usage
Dim instance As Win32FindDataW
Dim value As Long

value = instance.LastAccessTime

instance.LastAccessTime = value
```

**C++**<br />
``` C++
public:
long long LastAccessTime
```

**F#**<br />
``` F#
val mutable LastAccessTime: int64
```


#### Field Value
Type: Int64

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />