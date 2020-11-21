# ShellExecuteInfo.Verb Field
 

A string, referred to as a verb, that specifies the action to be performed. The set of available verbs depends on the particular file or folder. Generally, the actions available from an object's shortcut menu are available verbs. This parameter can be NULL, in which case the default verb is used if available. If not, the "open" verb is used. If neither verb is available, the system uses the first verb listed in the registry.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Verb
```

**VB**<br />
``` VB
Public Verb As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As String

value = instance.Verb

instance.Verb = value
```

**C++**<br />
``` C++
public:
String^ Verb
```

**F#**<br />
``` F#
val mutable Verb: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />