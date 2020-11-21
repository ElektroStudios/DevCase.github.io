# ProcessStartupInfo.Title Field
 

For console processes, this is the title displayed in the title bar if a new console window is created. 

 If NULL, the name of the executable file is used as the window title instead. 

 This parameter must be NULL for GUI or console processes that do not create a new console window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Title
```

**VB**<br />
``` VB
Public Title As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
Dim value As String

value = instance.Title

instance.Title = value
```

**C++**<br />
``` C++
public:
String^ Title
```

**F#**<br />
``` F#
val mutable Title: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />