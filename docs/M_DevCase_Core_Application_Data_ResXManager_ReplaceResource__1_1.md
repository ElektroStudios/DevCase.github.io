# ResXManager.ReplaceResource(*T*) Method (String, *T*, String)
 

Replaces a resource by the specified name of the specified type inside the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void ReplaceResource<T>(
	string name,
	T data,
	string comment = ""
)

```

**VB**<br />
``` VB
Public Overridable Sub ReplaceResource(Of T) ( 
	name As String,
	data As T,
	Optional comment As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim name As String
Dim data As T
Dim comment As String

instance.ReplaceResource(name, data, comment)
```

**C++**<br />
``` C++
public:
generic<typename T>
virtual void ReplaceResource(
	String^ name, 
	T data, 
	String^ comment = L""
)
```

**F#**<br />
``` F#
abstract ReplaceResource : 
        name : string * 
        data : 'T * 
        ?comment : string 
(* Defaults:
        let _comment = defaultArg comment ""
*)
-> unit 
override ReplaceResource : 
        name : string * 
        data : 'T * 
        ?comment : string 
(* Defaults:
        let _comment = defaultArg comment ""
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The resource name.</dd><dt>data</dt><dd>Type: *T*<br />The resource data.</dd><dt>comment (Optional)</dt><dd>Type: System.String<br />The resource comment.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Resource file not found.</td></tr><tr><td>ArgumentException</td><td>A resource with the same name already exists in the table.;name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="Overload_DevCase_Core_Application_Data_ResXManager_ReplaceResource">ReplaceResource Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />