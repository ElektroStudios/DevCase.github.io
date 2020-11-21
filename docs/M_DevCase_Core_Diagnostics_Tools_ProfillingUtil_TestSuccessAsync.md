# ProfillingUtil.TestSuccessAsync Method 
 

Tests the execution of a Action then returns a value that indicates whether the execution was successful.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<bool> TestSuccessAsync(
	Action action
)
```

**VB**<br />
``` VB
Public Shared Function TestSuccessAsync ( 
	action As Action
) As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim action As Action
Dim returnValue As Task(Of Boolean)

returnValue = ProfillingUtil.TestSuccessAsync(action)
```

**C++**<br />
``` C++
public:
static Task<bool>^ TestSuccessAsync(
	Action^ action
)
```

**F#**<br />
``` F#
static member TestSuccessAsync : 
        action : Action -> Task<bool> 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action<br />The Action to invoke.</dd></dl>

#### Return Value
Type: Task(Boolean)<br />`true` (`True` in Visual Basic) if execution was successful, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = TestSuccessAsync(Sub() Integer.Parse("qwerty")).Result
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />