# AppUtil.ReferencedAssemblies Property 
 

Gets the referenced assemblies of the current assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<AssemblyName> ReferencedAssemblies { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ReferencedAssemblies As ReadOnlyCollection(Of AssemblyName)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of AssemblyName)

value = AppUtil.ReferencedAssemblies

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<AssemblyName^>^ ReferencedAssemblies {
	ReadOnlyCollection<AssemblyName^>^ get ();
}
```

**F#**<br />
``` F#
static member ReferencedAssemblies : ReadOnlyCollection<AssemblyName> with get

```


#### Property Value
Type: ReadOnlyCollection(AssemblyName)<br />The loaded assemblies.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each assn As AssemblyName In ReferencedAssemblies

    Console.WriteLine(ass.Name)

Next assn
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />