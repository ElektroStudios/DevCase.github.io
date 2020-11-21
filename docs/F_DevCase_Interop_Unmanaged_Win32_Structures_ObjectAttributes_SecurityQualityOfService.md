# ObjectAttributes.SecurityQualityOfService Field
 

Optional quality of service to be applied to the object when it is created. Used to indicate the security impersonation level and context tracking mode (dynamic or static). 

 Currently, the InitializeObjectAttributes macro sets this member to Zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr SecurityQualityOfService
```

**VB**<br />
``` VB
Public SecurityQualityOfService As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ObjectAttributes
Dim value As IntPtr

value = instance.SecurityQualityOfService

instance.SecurityQualityOfService = value
```

**C++**<br />
``` C++
public:
IntPtr SecurityQualityOfService
```

**F#**<br />
``` F#
val mutable SecurityQualityOfService: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />