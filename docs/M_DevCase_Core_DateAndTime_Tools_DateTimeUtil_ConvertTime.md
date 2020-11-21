# DateTimeUtil.ConvertTime Method 
 

Converts between units of time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double ConvertTime(
	double value,
	TimeUnit fromUnit,
	TimeUnit toUnit
)
```

**VB**<br />
``` VB
Public Shared Function ConvertTime ( 
	value As Double,
	fromUnit As TimeUnit,
	toUnit As TimeUnit
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim value As Double
Dim fromUnit As TimeUnit
Dim toUnit As TimeUnit
Dim returnValue As Double

returnValue = DateTimeUtil.ConvertTime(value, 
	fromUnit, toUnit)
```

**C++**<br />
``` C++
public:
static double ConvertTime(
	double value, 
	TimeUnit fromUnit, 
	TimeUnit toUnit
)
```

**F#**<br />
``` F#
static member ConvertTime : 
        value : float * 
        fromUnit : TimeUnit * 
        toUnit : TimeUnit -> float 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Double<br />The time value.</dd><dt>fromUnit</dt><dd>Type: <a href="T_DevCase_Core_DateAndTime_TimeUnit">DevCase.Core.DateAndTime.TimeUnit</a><br />The source <a href="T_DevCase_Core_DateAndTime_TimeUnit">TimeUnit</a> unit.</dd><dt>toUnit</dt><dd>Type: <a href="T_DevCase_Core_DateAndTime_TimeUnit">DevCase.Core.DateAndTime.TimeUnit</a><br />The target <a href="T_DevCase_Core_DateAndTime_TimeUnit">TimeUnit</a> unit.</dd></dl>

#### Return Value
Type: Double<br />The resulting value of the conversion.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox(ConvertTime(1, TimeUnit.Hours, TimeUnit.Milliseconds)) ' Result: 3.600.000
MsgBox(ConvertTime(1, TimeUnit.Hours, TimeUnit.Seconds))      ' Result: 3.600
MsgBox(ConvertTime(1, TimeUnit.Hours, TimeUnit.Minutes))      ' Result: 60
MsgBox(ConvertTime(1, TimeUnit.Hours, TimeUnit.Hours))        ' Result: 1
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />