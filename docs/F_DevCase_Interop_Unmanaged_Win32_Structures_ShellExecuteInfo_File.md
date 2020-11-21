# ShellExecuteInfo.File Field
 

The address of a null-terminated string that specifies the name of the file or object on which ShellExecuteEx will perform the action specified by the lpVerb parameter. The system registry verbs that are supported by the ShellExecuteEx function include "open" for executable files and document files and "print" for document files for which a print handler has been registered. Other applications might have added Shell verbs through the system registry, such as "play" for .avi and .wav files. To specify a Shell Namespace DevCase.Interop.object, pass the fully qualified parse name and set the SEE_MASK_INVOKEIDLIST flag in the fMask parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string File
```

**VB**<br />
``` VB
Public File As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As String

value = instance.File

instance.File = value
```

**C++**<br />
``` C++
public:
String^ File
```

**F#**<br />
``` F#
val mutable File: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />