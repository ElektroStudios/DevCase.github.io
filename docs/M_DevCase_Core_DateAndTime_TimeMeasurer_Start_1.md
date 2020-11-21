# TimeMeasurer.Start Method (Double)
 

Starts the time interval measurement.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Start(
	double milliseconds
)
```

**VB**<br />
``` VB
Public Sub Start ( 
	milliseconds As Double
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TimeMeasurer
Dim milliseconds As Double

instance.Start(milliseconds)
```

**C++**<br />
``` C++
public:
void Start(
	double milliseconds
)
```

**F#**<br />
``` F#
member Start : 
        milliseconds : float -> unit 

```


#### Parameters
&nbsp;<dl><dt>milliseconds</dt><dd>Type: System.Double<br />The time interval to measure, in milliseconds.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>milliseconds;A value smaller than <a href="P_DevCase_Core_DateAndTime_TimeMeasurer_MaxValue">MaxValue</a> is required.</td></tr><tr><td>ArgumentOutOfRangeException</td><td>milliseconds;A value greater than 0 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_TimeMeasurer">TimeMeasurer Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_TimeMeasurer_Start">Start Overload</a><br /><a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime Namespace</a><br />