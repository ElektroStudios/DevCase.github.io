# DateTimeUtil.GetAge Method (DateTime, DateTime)
 

Gets the years old of a person at specified date from the specified birth date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int GetAge(
	DateTime birthDate,
	DateTime at
)
```

**VB**<br />
``` VB
Public Shared Function GetAge ( 
	birthDate As DateTime,
	at As DateTime
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim birthDate As DateTime
Dim at As DateTime
Dim returnValue As Integer

returnValue = DateTimeUtil.GetAge(birthDate, 
	at)
```

**C++**<br />
``` C++
public:
static int GetAge(
	DateTime birthDate, 
	DateTime at
)
```

**F#**<br />
``` F#
static member GetAge : 
        birthDate : DateTime * 
        at : DateTime -> int 

```


#### Parameters
&nbsp;<dl><dt>birthDate</dt><dd>Type: System.DateTime<br />The birth date.</dd><dt>at</dt><dd>Type: System.DateTime<br />\[Missing <param name="at"/> documentation for "M:DevCase.Core.DateAndTime.Tools.DateTimeUtil.GetAge(System.DateTime,System.DateTime)"\]</dd></dl>

#### Return Value
Type: Int32<br />The years old.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>at</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim birthdDate As Date = Date.ParseExact("08/09/1986", "dd/MM/yyyy", CultureInfo.InvariantCulture)
Dim age As Integer = GetAge(birthdDate, birthdDate.AddYears(20))
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetAge">GetAge Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />