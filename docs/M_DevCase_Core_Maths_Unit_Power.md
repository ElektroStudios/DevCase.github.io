# Unit.Power Method 
 

Raises the current <a href="T_DevCase_Core_Maths_Unit">Unit</a> to the specified power. 

 I.e. `Units.Length.Metre.Power(3)` would return a cubic metre unit.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Unit Power(
	int value
)
```

**VB**<br />
``` VB
Public Function Power ( 
	value As Integer
) As Unit
```

**VB Usage**<br />
``` VB Usage
Dim instance As Unit
Dim value As Integer
Dim returnValue As Unit

returnValue = instance.Power(value)
```

**C++**<br />
``` C++
public:
Unit^ Power(
	int value
)
```

**F#**<br />
``` F#
member Power : 
        value : int -> Unit 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Int32<br />The value.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Unit">Unit</a><br />The resulting <a href="T_DevCase_Core_Maths_Unit">Unit</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />