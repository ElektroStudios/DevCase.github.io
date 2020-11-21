# CommandLineArgumentsNotifier Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_CommandLineArgumentsNotifier">CommandLineArgumentsNotifier</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineArgumentsNotifier(
	bool notifyCurrentArguments
)
```

**VB**<br />
``` VB
Public Sub New ( 
	notifyCurrentArguments As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim notifyCurrentArguments As Boolean

Dim instance As New CommandLineArgumentsNotifier(notifyCurrentArguments)
```

**C++**<br />
``` C++
public:
CommandLineArgumentsNotifier(
	bool notifyCurrentArguments
)
```

**F#**<br />
``` F#
new : 
        notifyCurrentArguments : bool -> CommandLineArgumentsNotifier
```


#### Parameters
&nbsp;<dl><dt>notifyCurrentArguments</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), imminently fires the <a href="E_DevCase_Core_Application_CommandLineArgumentsNotifier_ArgumentsReceived">ArgumentsReceived</a> event using the current command-line arguments of the application as its event data.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineArgumentsNotifier">CommandLineArgumentsNotifier Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />