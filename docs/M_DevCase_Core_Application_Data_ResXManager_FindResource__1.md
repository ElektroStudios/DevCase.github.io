# ResXManager.FindResource(*T*) Method (String, StringComparison)
 

Finds a resource by the specified name of specified type inside the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Resource<T> FindResource<T>(
	string name,
	StringComparison stringComparison = StringComparison.OrdinalIgnoreCase
)

```

**VB**<br />
``` VB
Public Overridable Function FindResource(Of T) ( 
	name As String,
	Optional stringComparison As StringComparison = StringComparison.OrdinalIgnoreCase
) As Resource(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim name As String
Dim stringComparison As StringComparison
Dim returnValue As Resource(Of T)

returnValue = instance.FindResource(name, 
	stringComparison)
```

**C++**<br />
``` C++
public:
generic<typename T>
virtual Resource<T>^ FindResource(
	String^ name, 
	StringComparison stringComparison = StringComparison::OrdinalIgnoreCase
)
```

**F#**<br />
``` F#
abstract FindResource : 
        name : string * 
        ?stringComparison : StringComparison 
(* Defaults:
        let _stringComparison = defaultArg stringComparison StringComparison.OrdinalIgnoreCase
*)
-> Resource<'T> 
override FindResource : 
        name : string * 
        ?stringComparison : StringComparison 
(* Defaults:
        let _stringComparison = defaultArg stringComparison StringComparison.OrdinalIgnoreCase
*)
-> Resource<'T> 
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The resource name.</dd><dt>stringComparison (Optional)</dt><dd>Type: System.StringComparison<br />The StringComparison to compare the resource name.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_Data_Resource_1">Resource</a>(*T*)<br />The resource.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Resource file not found.</td></tr><tr><td>ArgumentException</td><td>Resource with the specified name is not found.;name</td></tr><tr><td>ArgumentException</td><td>The specified Type differs from the resource Type.;T</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="Overload_DevCase_Core_Application_Data_ResXManager_FindResource">FindResource Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />