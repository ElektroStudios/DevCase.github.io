# Win32FindDataW.FileSizeHigh Field
 

The high-order DWORD value of the file size, in bytes. 

 This value is zero unless the file size is greater than MAXDWORD. 

 The size of the file is equal to (FileSizeHigh * (MAXDWORD+1)) + FileSizeLow.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint FileSizeHigh
```

**VB**<br />
``` VB
Public FileSizeHigh As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As Win32FindDataW
Dim value As UInteger

value = instance.FileSizeHigh

instance.FileSizeHigh = value
```

**C++**<br />
``` C++
public:
unsigned int FileSizeHigh
```

**F#**<br />
``` F#
val mutable FileSizeHigh: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />