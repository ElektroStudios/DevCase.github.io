# ResXManager.AddResource(*T*) Method (Resource(*T*))
 

Adds a resource into the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void AddResource<T>(
	Resource<T> resource
)

```

**VB**<br />
``` VB
Public Overridable Sub AddResource(Of T) ( 
	resource As Resource(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim resource As Resource(Of T)

instance.AddResource(resource)
```

**C++**<br />
``` C++
public:
generic<typename T>
virtual void AddResource(
	Resource<T>^ resource
)
```

**F#**<br />
``` F#
abstract AddResource : 
        resource : Resource<'T> -> unit 
override AddResource : 
        resource : Resource<'T> -> unit 
```


#### Parameters
&nbsp;<dl><dt>resource</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_Resource_1">DevCase.Core.Application.Data.Resource</a>(*T*)<br />The resource.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Resource file not found.</td></tr><tr><td>ArgumentException</td><td>A resource with the same name already exists in the table.;name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="Overload_DevCase_Core_Application_Data_ResXManager_AddResource">AddResource Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />