# EnvironmentPathUtil.PathExtExists Method 
 

Determines whether the `PATHEXT` value exists on the registry of the specified user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PathExtExists(
	RegistryScope scope
)
```

**VB**<br />
``` VB
Public Shared Function PathExtExists ( 
	scope As RegistryScope
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim returnValue As Boolean

returnValue = EnvironmentPathUtil.PathExtExists(scope)
```

**C++**<br />
``` C++
public:
static bool PathExtExists(
	RegistryScope scope
)
```

**F#**<br />
``` F#
static member PathExtExists : 
        scope : RegistryScope -> bool 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if `PATHEXT` value exists, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />