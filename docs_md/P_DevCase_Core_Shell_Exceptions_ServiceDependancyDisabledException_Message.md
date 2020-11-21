# ServiceDependancyDisabledException.Message Property 
 

Gets a message that describes the current exception.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override string Message { get; }
```

**VB**<br />
``` VB
Public Overrides ReadOnly Property Message As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ServiceDependancyDisabledException
Dim value As String

value = instance.Message

```

**C++**<br />
``` C++
public:
virtual property String^ Message {
	String^ get () override;
}
```

**F#**<br />
``` F#
abstract Message : string with get
override Message : string with get
```


#### Property Value
Type: String<br />The message.

#### Implements
_Exception.Message<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException">ServiceDependancyDisabledException Class</a><br /><a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions Namespace</a><br />