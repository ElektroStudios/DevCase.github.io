# ResXManager.FindResources(*T*) Method 
 

Finds the resources of the specified type inside the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IEnumerable<Resource<T>> FindResources<T>()

```

**VB**<br />
``` VB
Public Overridable Function FindResources(Of T) As IEnumerable(Of Resource(Of T))
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim returnValue As IEnumerable(Of Resource(Of T))

returnValue = instance.FindResources()
```

**C++**<br />
``` C++
public:
generic<typename T>
virtual IEnumerable<Resource<T>^>^ FindResources()
```

**F#**<br />
``` F#
abstract FindResources : unit -> IEnumerable<Resource<'T>> 
override FindResources : unit -> IEnumerable<Resource<'T>> 
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_Application_Data_Resource_1">Resource</a>(*T*))<br />The resource.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Resource file not found.</td></tr><tr><td>ArgumentException</td><td>Resource with the specified name is not found.;name</td></tr><tr><td>ArgumentException</td><td>The specified Type differs from the resource Type.;T</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />