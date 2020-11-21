# ChangeFilter.ExtStatus Field
 

If the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function succeeds, this field contains information about the success.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MessageFilterInfo ExtStatus
```

**VB**<br />
``` VB
Public ExtStatus As MessageFilterInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ChangeFilter
Dim value As MessageFilterInfo

value = instance.ExtStatus

instance.ExtStatus = value
```

**C++**<br />
``` C++
public:
MessageFilterInfo ExtStatus
```

**F#**<br />
``` F#
val mutable ExtStatus: MessageFilterInfo
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MessageFilterInfo">MessageFilterInfo</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter">ChangeFilter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />