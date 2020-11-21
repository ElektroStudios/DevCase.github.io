# MouseLowLevelHookStruct.MouseData Field
 

If the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseWheel</a>, the high-order word of this member is the wheel delta. 

 ( The low-order word is reserved. ) 

 A positive value indicates that the wheel was rotated forward, away from the user; a negative value indicates that the wheel was rotated backward, toward the user. 

 One wheel click is defined as `WHEEL_DELTA`, which is `120`. 





 If the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonUp</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonDblClk</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonUp</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonDblClk</a>, the high-order word specifies which X button was pressed or released, and the low-order word is reserved. 

 This value can be one or more of the following values. Otherwise, mouseData is not used.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int MouseData
```

**VB**<br />
``` VB
Public MouseData As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseLowLevelHookStruct
Dim value As Integer

value = instance.MouseData

instance.MouseData = value
```

**C++**<br />
``` C++
public:
int MouseData
```

**F#**<br />
``` F#
val mutable MouseData: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct">MouseLowLevelHookStruct Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />