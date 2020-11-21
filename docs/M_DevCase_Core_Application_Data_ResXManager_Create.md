# ResXManager.Create Method 
 

Creates the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Create(
	bool overwrite = false
)
```

**VB**<br />
``` VB
Public Overridable Sub Create ( 
	Optional overwrite As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim overwrite As Boolean

instance.Create(overwrite)
```

**C++**<br />
``` C++
public:
virtual void Create(
	bool overwrite = false
)
```

**F#**<br />
``` F#
abstract Create : 
        ?overwrite : bool 
(* Defaults:
        let _overwrite = defaultArg overwrite false
*)
-> unit 
override Create : 
        ?overwrite : bool 
(* Defaults:
        let _overwrite = defaultArg overwrite false
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>overwrite (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), overwrites any existent file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>Resource file already exists.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />