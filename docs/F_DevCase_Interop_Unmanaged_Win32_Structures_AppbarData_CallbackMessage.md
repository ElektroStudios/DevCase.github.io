# AppbarData.CallbackMessage Field
 

An application-defined message identifier. 

 The application uses the specified identifier for notification messages that it sends to the appbar identified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_Hwnd">Hwnd</a> member. 

 This member is used when sending the `ABM_NEW` message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int CallbackMessage
```

**VB**<br />
``` VB
Public CallbackMessage As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppbarData
Dim value As Integer

value = instance.CallbackMessage

instance.CallbackMessage = value
```

**C++**<br />
``` C++
public:
int CallbackMessage
```

**F#**<br />
``` F#
val mutable CallbackMessage: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData">AppbarData Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />