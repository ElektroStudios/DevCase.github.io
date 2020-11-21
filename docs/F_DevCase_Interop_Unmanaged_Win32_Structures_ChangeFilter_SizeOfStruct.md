# ChangeFilter.SizeOfStruct Field
 

The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of ChangeFilter)`, otherwise the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint SizeOfStruct
```

**VB**<br />
``` VB
Public SizeOfStruct As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As ChangeFilter
Dim value As UInteger

value = instance.SizeOfStruct

instance.SizeOfStruct = value
```

**C++**<br />
``` C++
public:
unsigned int SizeOfStruct
```

**F#**<br />
``` F#
val mutable SizeOfStruct: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter">ChangeFilter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />