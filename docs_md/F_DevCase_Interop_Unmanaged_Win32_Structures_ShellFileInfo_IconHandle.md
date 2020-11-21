# ShellFileInfo.IconHandle Field
 

A handle to the icon that represents the file. 

 You are responsible for destroying this handle with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyIcon">DestroyIcon(IntPtr)</a> when you no longer need it.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr IconHandle
```

**VB**<br />
``` VB
Public IconHandle As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellFileInfo
Dim value As IntPtr

value = instance.IconHandle

instance.IconHandle = value
```

**C++**<br />
``` C++
public:
IntPtr IconHandle
```

**F#**<br />
``` F#
val mutable IconHandle: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo">ShellFileInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />