# DateTimeUtil.GetAge Method (DateTime)
 

Gets the current years old of a person from the specified birth date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int GetAge(
	DateTime birthDate
)
```

**VB**<br />
``` VB
Public Shared Function GetAge ( 
	birthDate As DateTime
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim birthDate As DateTime
Dim returnValue As Integer

returnValue = DateTimeUtil.GetAge(birthDate)
```

**C++**<br />
``` C++
public:
static int GetAge(
	DateTime birthDate
)
```

**F#**<br />
``` F#
static member GetAge : 
        birthDate : DateTime -> int 

```


#### Parameters
&nbsp;<dl><dt>birthDate</dt><dd>Type: System.DateTime<br />The birth date.</dd></dl>

#### Return Value
Type: Int32<br />The years old.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>at</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim birthdDate As Date = Date.ParseExact("08/09/1986", "dd/MM/yyyy", CultureInfo.InvariantCulture)
Dim age As Integer = GetAge(birthdDate)
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetAge">GetAge Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />