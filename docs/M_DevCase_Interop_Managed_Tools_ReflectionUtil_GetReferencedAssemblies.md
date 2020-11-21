# ReflectionUtil.GetReferencedAssemblies Method 
 

Gets the referenced assemblies of the specified assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<AssemblyName> GetReferencedAssemblies(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetReferencedAssemblies ( 
	filepath As String
) As ReadOnlyCollection(Of AssemblyName)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As ReadOnlyCollection(Of AssemblyName)

returnValue = ReflectionUtil.GetReferencedAssemblies(filepath)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<AssemblyName^>^ GetReferencedAssemblies(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetReferencedAssemblies : 
        filepath : string -> ReadOnlyCollection<AssemblyName> 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(AssemblyName)<br />The referenced assemblies of the specified assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each assn As AssemblyName In GetReferencedAssemblies("C:\Assembly.exe")

    Console.WriteLine(assn.Name)

Next assn
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_ReflectionUtil">ReflectionUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />