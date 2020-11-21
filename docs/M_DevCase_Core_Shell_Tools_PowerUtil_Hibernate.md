# PowerUtil.Hibernate Method 
 

Sets the system in Hibernate state.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Hibernate(
	bool force = false
)
```

**VB**<br />
``` VB
Public Shared Sub Hibernate ( 
	Optional force As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim force As BooleanPowerUtil.Hibernate(force)
```

**C++**<br />
``` C++
public:
static void Hibernate(
	bool force = false
)
```

**F#**<br />
``` F#
static member Hibernate : 
        ?force : bool 
(* Defaults:
        let _force = defaultArg force false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>force (Optional)</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to force the Hibernate mode immediately; `false` (`False` in Visual Basic) to cause the operating system to send a Hibernate request to every application.</dd></dl>

## Remarks
If an application does not respond to a Hibernate request within 20 seconds, the operating system determines that it is in a non-responsive state, and that the application can either be put to sleep or terminated. 

 Once an application responds to a Hibernate request, it can take whatever time it needs to clean up resources and shut down active processes.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />