# DateTimeUtil.TimeDiff Method 
 

Calculates the difference between two intervals of time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TimeSpan TimeDiff(
	TimeSpan startTime,
	TimeSpan endTime
)
```

**VB**<br />
``` VB
Public Shared Function TimeDiff ( 
	startTime As TimeSpan,
	endTime As TimeSpan
) As TimeSpan
```

**VB Usage**<br />
``` VB Usage
Dim startTime As TimeSpan
Dim endTime As TimeSpan
Dim returnValue As TimeSpan

returnValue = DateTimeUtil.TimeDiff(startTime, 
	endTime)
```

**C++**<br />
``` C++
public:
static TimeSpan TimeDiff(
	TimeSpan startTime, 
	TimeSpan endTime
)
```

**F#**<br />
``` F#
static member TimeDiff : 
        startTime : TimeSpan * 
        endTime : TimeSpan -> TimeSpan 

```


#### Parameters
&nbsp;<dl><dt>startTime</dt><dd>Type: System.TimeSpan<br />The start time.</dd><dt>endTime</dt><dd>Type: System.TimeSpan<br />The end time.</dd></dl>

#### Return Value
Type: TimeSpan<br />A TimeSpan that contains the time difference.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ts1 As TimeSpan = TimeSpan.FromHours(0)
Dim ts2 As TimeSpan = TimeSpan.FromHours(1)
Dim diff As TimeSpan = DateTimeUtil.TimeDiff(ts1, ts2)
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />