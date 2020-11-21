# TimeMeasurer.Start Method (DateTime, DateTime)
 

Starts a time interval measurement given a difference between two dates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Start(
	DateTime startDate,
	DateTime endDate
)
```

**VB**<br />
``` VB
Public Sub Start ( 
	startDate As DateTime,
	endDate As DateTime
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TimeMeasurer
Dim startDate As DateTime
Dim endDate As DateTime

instance.Start(startDate, endDate)
```

**C++**<br />
``` C++
public:
void Start(
	DateTime startDate, 
	DateTime endDate
)
```

**F#**<br />
``` F#
member Start : 
        startDate : DateTime * 
        endDate : DateTime -> unit 

```


#### Parameters
&nbsp;<dl><dt>startDate</dt><dd>Type: System.DateTime<br />The starting date.</dd><dt>endDate</dt><dd>Type: System.DateTime<br />The ending date.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_TimeMeasurer">TimeMeasurer Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_TimeMeasurer_Start">Start Overload</a><br /><a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime Namespace</a><br />