# DateTimeUtil.DateDiff Method 
 

Calculates the difference between two dates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TimeSpan DateDiff(
	DateTime startDate,
	DateTime endDate
)
```

**VB**<br />
``` VB
Public Shared Function DateDiff ( 
	startDate As DateTime,
	endDate As DateTime
) As TimeSpan
```

**VB Usage**<br />
``` VB Usage
Dim startDate As DateTime
Dim endDate As DateTime
Dim returnValue As TimeSpan

returnValue = DateTimeUtil.DateDiff(startDate, 
	endDate)
```

**C++**<br />
``` C++
public:
static TimeSpan DateDiff(
	DateTime startDate, 
	DateTime endDate
)
```

**F#**<br />
``` F#
static member DateDiff : 
        startDate : DateTime * 
        endDate : DateTime -> TimeSpan 

```


#### Parameters
&nbsp;<dl><dt>startDate</dt><dd>Type: System.DateTime<br />The start date.</dd><dt>endDate</dt><dd>Type: System.DateTime<br />The end date.</dd></dl>

#### Return Value
Type: TimeSpan<br />A TimeSpan that contains the time difference.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim date1 As Date = Date.Now
Dim date2 As Date = Date.Now.AddHours(1)
Dim diff As TimeSpan = DateTimeUtil.DateDiff(date1, date2)
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />