# ShellExecuteInfo.Process Field
 

A handle to the monitor upon which the document is to be displayed. This member is ignored if fMask does not include SEE_MASK_HMONITOR.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr Process
```

**VB**<br />
``` VB
Public Process As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As IntPtr

value = instance.Process

instance.Process = value
```

**C++**<br />
``` C++
public:
IntPtr Process
```

**F#**<br />
``` F#
val mutable Process: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />