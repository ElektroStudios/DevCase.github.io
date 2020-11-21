# CommandLineArgumentsEventArgs.Arguments Property 
 

Gets the command-line arguments of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<string> Arguments { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Arguments As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineArgumentsEventArgs
Dim value As ReadOnlyCollection(Of String)

value = instance.Arguments

```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<String^>^ Arguments {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
member Arguments : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />The command-line arguments of the current application.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Eventing_CommandLineArgumentsEventArgs">CommandLineArgumentsEventArgs Class</a><br /><a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing Namespace</a><br />