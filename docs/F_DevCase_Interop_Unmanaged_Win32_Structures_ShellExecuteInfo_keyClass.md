# ShellExecuteInfo.keyClass Field
 

A handle to the registry key for the file type. The access rights for this registry key should be set to KEY_READ. This member is ignored if fMask does not include SEE_MASK_CLASSKEY.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr keyClass
```

**VB**<br />
``` VB
Public keyClass As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As IntPtr

value = instance.keyClass

instance.keyClass = value
```

**C++**<br />
``` C++
public:
IntPtr keyClass
```

**F#**<br />
``` F#
val mutable keyClass: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />