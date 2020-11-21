# ResXManager.RemoveResource Method 
 

Removes a resource by the specified name from the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RemoveResource(
	string name,
	StringComparison stringComparison = StringComparison.OrdinalIgnoreCase
)
```

**VB**<br />
``` VB
Public Overridable Sub RemoveResource ( 
	name As String,
	Optional stringComparison As StringComparison = StringComparison.OrdinalIgnoreCase
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim name As String
Dim stringComparison As StringComparison

instance.RemoveResource(name, stringComparison)
```

**C++**<br />
``` C++
public:
virtual void RemoveResource(
	String^ name, 
	StringComparison stringComparison = StringComparison::OrdinalIgnoreCase
)
```

**F#**<br />
``` F#
abstract RemoveResource : 
        name : string * 
        ?stringComparison : StringComparison 
(* Defaults:
        let _stringComparison = defaultArg stringComparison StringComparison.OrdinalIgnoreCase
*)
-> unit 
override RemoveResource : 
        name : string * 
        ?stringComparison : StringComparison 
(* Defaults:
        let _stringComparison = defaultArg stringComparison StringComparison.OrdinalIgnoreCase
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The resource name.</dd><dt>stringComparison (Optional)</dt><dd>Type: System.StringComparison<br />The StringComparison to compare the resource name.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Resource file not found.</td></tr><tr><td>ArgumentException</td><td>Any resource found matching the specified name.;name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />