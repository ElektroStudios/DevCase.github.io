# DateTimeUtil.GetRandomDateTime Method (DateTime)
 

Gets a random DateTime in range between MinValue and the specified date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTime GetRandomDateTime(
	DateTime dateMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomDateTime ( 
	dateMax As DateTime
) As DateTime
```

**VB Usage**<br />
``` VB Usage
Dim dateMax As DateTime
Dim returnValue As DateTime

returnValue = DateTimeUtil.GetRandomDateTime(dateMax)
```

**C++**<br />
``` C++
public:
static DateTime GetRandomDateTime(
	DateTime dateMax
)
```

**F#**<br />
``` F#
static member GetRandomDateTime : 
        dateMax : DateTime -> DateTime 

```


#### Parameters
&nbsp;<dl><dt>dateMax</dt><dd>Type: System.DateTime<br />The maximum DateTime.</dd></dl>

#### Return Value
Type: DateTime<br />The resulting DateTime.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim maxDate As Date = Date.MaxValue
Dim ramdomDate As Date = GetRandomDateTime(maxDate)

Console.WriteLine(randomDate.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetRandomDateTime">GetRandomDateTime Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />