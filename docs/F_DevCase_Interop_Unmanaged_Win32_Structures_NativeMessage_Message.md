# NativeMessage.Message Field
 

The message identifier. Applications can only use the low word; the high word is reserved by the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint Message
```

**VB**<br />
``` VB
Public Message As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeMessage
Dim value As UInteger

value = instance.Message

instance.Message = value
```

**C++**<br />
``` C++
public:
unsigned int Message
```

**F#**<br />
``` F#
val mutable Message: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />