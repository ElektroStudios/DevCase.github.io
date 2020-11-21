# ServicingUtil.Services Property 
 

Gets all the services of the local computer, except for the device driver services.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<ServiceController> Services { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Services As ReadOnlyCollection(Of ServiceController)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of ServiceController)

value = ServicingUtil.Services

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<ServiceController^>^ Services {
	ReadOnlyCollection<ServiceController^>^ get ();
}
```

**F#**<br />
``` F#
static member Services : ReadOnlyCollection<ServiceController> with get

```


#### Property Value
Type: ReadOnlyCollection(ServiceController)<br />The services of the local computer, except for the device driver services.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />