# ShellExecuteInfo.Class Field
 

The address of a null-terminated string that specifies one of the following A ProgId. For example, "Paint.Picture". A URI protocol scheme. For example, "http". A file extension. For example, ".txt". A registry path under HKEY_CLASSES_ROOT that names a subkey that contains one or more Shell verbs. This key will have a subkey that conforms to the Shell verb registry schema, such as shell\verb name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Class
```

**VB**<br />
``` VB
Public Class As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As String

value = instance.Class

instance.Class = value
```

**C++**<br />
``` C++
public:
String^ Class
```

**F#**<br />
``` F#
val mutable Class: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />