# CommandLineArgumentsNotifier.Arguments Property 
 

Gets or sets the command-line arguments of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<string> Arguments { get; set; }
```

**VB**<br />
``` VB
Public Property Arguments As ReadOnlyCollection(Of String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineArgumentsNotifier
Dim value As ReadOnlyCollection(Of String)

value = instance.Arguments

instance.Arguments = value
```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<String^>^ Arguments {
	ReadOnlyCollection<String^>^ get ();
	void set (ReadOnlyCollection<String^>^ value);
}
```

**F#**<br />
``` F#
member Arguments : ReadOnlyCollection<string> with get, set

```


#### Property Value
Type: ReadOnlyCollection(String)<br />The command-line arguments of the current application.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineArgumentsNotifier">CommandLineArgumentsNotifier Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />