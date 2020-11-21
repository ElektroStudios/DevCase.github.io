# ShellExecuteInfo.Show Field
 

Required. Flags that specify how an application is to be shown when it is opened; one of the SW_ values listed for the ShellExecute function. If lpFile specifies a document file, the flag is simply passed to the associated application. It is up to the application to decide how to handle it.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WindowShowCommand Show
```

**VB**<br />
``` VB
Public Show As WindowShowCommand
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As WindowShowCommand

value = instance.Show

instance.Show = value
```

**C++**<br />
``` C++
public:
WindowShowCommand Show
```

**F#**<br />
``` F#
val mutable Show: WindowShowCommand
```


#### Field Value
Type: WindowShowCommand

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />