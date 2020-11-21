# ShellExecuteInfo.Parameters Field
 

Optional. The address of a null-terminated string that contains the application parameters. The parameters must be separated by spaces. If the lpFile member specifies a document file, lpParameters should be NULL.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Parameters
```

**VB**<br />
``` VB
Public Parameters As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As String

value = instance.Parameters

instance.Parameters = value
```

**C++**<br />
``` C++
public:
String^ Parameters
```

**F#**<br />
``` F#
val mutable Parameters: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />