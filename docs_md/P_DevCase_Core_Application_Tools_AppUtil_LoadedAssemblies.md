# AppUtil.LoadedAssemblies Property 
 

Gets the loaded assemblies of the current assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<Assembly> LoadedAssemblies { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property LoadedAssemblies As ReadOnlyCollection(Of Assembly)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of Assembly)

value = AppUtil.LoadedAssemblies

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<Assembly^>^ LoadedAssemblies {
	ReadOnlyCollection<Assembly^>^ get ();
}
```

**F#**<br />
``` F#
static member LoadedAssemblies : ReadOnlyCollection<Assembly> with get

```


#### Property Value
Type: ReadOnlyCollection(Assembly)<br />The loaded assemblies.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each asm As Assembly In LoadedAssemblies
    Console.WriteLine(asm.GetName.Name)
Next ass
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />