# CommandLineArgumentsNotifier.ArgumentsReceived Event
 

Occurs when the application receives new command-line arguments.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static event EventHandler<CommandLineArgumentsEventArgs> ArgumentsReceived
```

**VB**<br />
``` VB
Public Shared Event ArgumentsReceived As EventHandler(Of CommandLineArgumentsEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim handler As EventHandler(Of CommandLineArgumentsEventArgs)

AddHandler CommandLineArgumentsNotifier.ArgumentsReceived, handler

```

**C++**<br />
``` C++
public:
static  event EventHandler<CommandLineArgumentsEventArgs^>^ ArgumentsReceived {
	void add (EventHandler<CommandLineArgumentsEventArgs^>^ value);
	void remove (EventHandler<CommandLineArgumentsEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ArgumentsReceived : IEvent<EventHandler<CommandLineArgumentsEventArgs>,
    CommandLineArgumentsEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Application_Eventing_CommandLineArgumentsEventArgs">CommandLineArgumentsEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineArgumentsNotifier">CommandLineArgumentsNotifier Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />