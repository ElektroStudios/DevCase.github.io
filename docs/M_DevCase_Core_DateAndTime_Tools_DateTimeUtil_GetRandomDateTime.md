# DateTimeUtil.GetRandomDateTime Method 
 

Gets a random DateTime in range between MinValue and MaxValue.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTime GetRandomDateTime()
```

**VB**<br />
``` VB
Public Shared Function GetRandomDateTime As DateTime
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As DateTime

returnValue = DateTimeUtil.GetRandomDateTime()
```

**C++**<br />
``` C++
public:
static DateTime GetRandomDateTime()
```

**F#**<br />
``` F#
static member GetRandomDateTime : unit -> DateTime 

```


#### Return Value
Type: DateTime<br />The resulting DateTime.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ramdomDate As Date = GetRandomDateTime()

Console.WriteLine(randomDate.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_GetRandomDateTime">GetRandomDateTime Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />