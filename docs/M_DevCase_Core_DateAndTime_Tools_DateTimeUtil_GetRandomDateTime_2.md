# DateTimeUtil.GetRandomDateTime Method (DateTime, DateTime)
 

Gets a random DateTime in range between the specified two dates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTime GetRandomDateTime(
	DateTime dateMin,
	DateTime dateMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomDateTime ( 
	dateMin As DateTime,
	dateMax As DateTime
) As DateTime
```

**VB Usage**<br />
``` VB Usage
Dim dateMin As DateTime
Dim dateMax As DateTime
Dim returnValue As DateTime

returnValue = DateTimeUtil.GetRandomDateTime(dateMin, 
	dateMax)
```

**C++**<br />
``` C++
public:
static DateTime GetRandomDateTime(
	DateTime dateMin, 
	DateTime dateMax
)
```

**F#**<br />
``` F#
static member GetRandomDateTime : 
        dateMin : DateTime * 
        dateMax : DateTime -> DateTime 

```


#### Parameters
&nbsp;<dl><dt>dateMin</dt><dd>Type: System.DateTime<br />The minimum DateTime.</dd><dt>dateMax</dt><dd>Type: System.DateTime<br />The maximum DateTime.</dd></dl>

#### Return Value
Type: DateTime<br />The resulting DateTime.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim minDate As Date = Date.MinValue
Dim maxDate As Date = Date.MaxValue
Dim ramdomDate As Date = GetRandomDateTime(minDate, maxDate)

Console.WriteLine(randomDate.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetRandomDateTime">GetRandomDateTime Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />