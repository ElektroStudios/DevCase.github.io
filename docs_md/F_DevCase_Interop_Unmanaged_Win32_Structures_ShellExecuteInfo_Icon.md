# ShellExecuteInfo.Icon Field
 

A handle to the icon for the file type. This member is ignored if fMask does not include SEE_MASK_ICON. This value is used only in Windows XP and earlier. It is ignored as of Windows Vista.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr Icon
```

**VB**<br />
``` VB
Public Icon As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As IntPtr

value = instance.Icon

instance.Icon = value
```

**C++**<br />
``` C++
public:
IntPtr Icon
```

**F#**<br />
``` F#
val mutable Icon: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />