# TimeMeasurerUpdatedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_DateAndTime_Eventing_TimeMeasurerUpdatedEventArgs">TimeMeasurerUpdatedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Eventing">DevCase.Core.DateAndTime.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TimeMeasurerUpdatedEventArgs(
	TimeSpan elapsed,
	TimeSpan remaining,
	TimeSpan goal
)
```

**VB**<br />
``` VB
Public Sub New ( 
	elapsed As TimeSpan,
	remaining As TimeSpan,
	goal As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim elapsed As TimeSpan
Dim remaining As TimeSpan
Dim goal As TimeSpan

Dim instance As New TimeMeasurerUpdatedEventArgs(elapsed, 
	remaining, goal)
```

**C++**<br />
``` C++
public:
TimeMeasurerUpdatedEventArgs(
	TimeSpan elapsed, 
	TimeSpan remaining, 
	TimeSpan goal
)
```

**F#**<br />
``` F#
new : 
        elapsed : TimeSpan * 
        remaining : TimeSpan * 
        goal : TimeSpan -> TimeMeasurerUpdatedEventArgs
```


#### Parameters
&nbsp;<dl><dt>elapsed</dt><dd>Type: System.TimeSpan<br />The elapsed time.</dd><dt>remaining</dt><dd>Type: System.TimeSpan<br />The remaining time.</dd><dt>goal</dt><dd>Type: System.TimeSpan<br />The goal time.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Eventing_TimeMeasurerUpdatedEventArgs">TimeMeasurerUpdatedEventArgs Class</a><br /><a href="N_DevCase_Core_DateAndTime_Eventing">DevCase.Core.DateAndTime.Eventing Namespace</a><br />