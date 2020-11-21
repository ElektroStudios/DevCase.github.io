# CommandLineArgumentsEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Eventing_CommandLineArgumentsEventArgs">CommandLineArgumentsEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineArgumentsEventArgs(
	ReadOnlyCollection<string> arguments
)
```

**VB**<br />
``` VB
Public Sub New ( 
	arguments As ReadOnlyCollection(Of String)
)
```

**VB Usage**<br />
``` VB Usage
Dim arguments As ReadOnlyCollection(Of String)

Dim instance As New CommandLineArgumentsEventArgs(arguments)
```

**C++**<br />
``` C++
public:
CommandLineArgumentsEventArgs(
	ReadOnlyCollection<String^>^ arguments
)
```

**F#**<br />
``` F#
new : 
        arguments : ReadOnlyCollection<string> -> CommandLineArgumentsEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.Collections.ObjectModel.ReadOnlyCollection(String)<br />The command-line arguments of the current application.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Eventing_CommandLineArgumentsEventArgs">CommandLineArgumentsEventArgs Class</a><br /><a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing Namespace</a><br />