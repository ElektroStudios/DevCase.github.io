# ShellExecuteInfo.HotKey Field
 

A keyboard shortcut to associate with the application. The low-order word is the virtual key code, and the high-order word is a modifier flag (HOTKEYF_). For a list of modifier flags, see the description of the WM_SETHOTKEY message. This member is ignored if fMask does not include SEE_MASK_HOTKEY.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int HotKey
```

**VB**<br />
``` VB
Public HotKey As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As Integer

value = instance.HotKey

instance.HotKey = value
```

**C++**<br />
``` C++
public:
int HotKey
```

**F#**<br />
``` F#
val mutable HotKey: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />