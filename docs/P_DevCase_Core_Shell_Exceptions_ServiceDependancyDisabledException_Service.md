# ServiceDependancyDisabledException.Service Property 
 

Gets the service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ServiceController Service { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Service As ServiceController
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ServiceDependancyDisabledException
Dim value As ServiceController

value = instance.Service

```

**C++**<br />
``` C++
public:
property ServiceController^ Service {
	ServiceController^ get ();
}
```

**F#**<br />
``` F#
member Service : ServiceController with get

```


#### Property Value
Type: ServiceController<br />The service.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Exceptions_ServiceDependancyDisabledException">ServiceDependancyDisabledException Class</a><br /><a href="N_DevCase_Core_Shell_Exceptions">DevCase.Core.Shell.Exceptions Namespace</a><br />