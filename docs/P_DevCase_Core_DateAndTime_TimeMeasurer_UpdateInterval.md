# TimeMeasurer.UpdateInterval Property 
 

Gets or sets the update interval. Maximum value is 1000 (1 second).

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int UpdateInterval { get; set; }
```

**VB**<br />
``` VB
Public Property UpdateInterval As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As TimeMeasurer
Dim value As Integer

value = instance.UpdateInterval

instance.UpdateInterval = value
```

**C++**<br />
``` C++
public:
property int UpdateInterval {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member UpdateInterval : int with get, set

```


#### Property Value
Type: Int32<br />The update interval.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>A value smaller than 1000 is required.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_TimeMeasurer">TimeMeasurer Class</a><br /><a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime Namespace</a><br />