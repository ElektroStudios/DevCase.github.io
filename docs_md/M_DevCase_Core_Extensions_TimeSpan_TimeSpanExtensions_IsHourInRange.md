# TimeSpanExtensions.IsHourInRange Method (TimeSpan, TimeRange)
 

Determine whether the current time (hours, minutes, seconds and milliseconds, not including days) in the source TimeSpan is in range between the specified start time and end time range.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TimeSpan">DevCase.Core.Extensions.TimeSpan</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsHourInRange(
	this TimeSpan sender,
	TimeRange range
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsHourInRange ( 
	sender As TimeSpan,
	range As TimeRange
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As TimeSpan
Dim range As TimeRange
Dim returnValue As Boolean

returnValue = sender.IsHourInRange(range)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsHourInRange(
	TimeSpan sender, 
	TimeRange^ range
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsHourInRange : 
        sender : TimeSpan * 
        range : TimeRange -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.TimeSpan<br />The source TimeSpan.</dd><dt>range</dt><dd>Type: <a href="T_DevCase_Core_DateAndTime_TimeRange">DevCase.Core.DateAndTime.TimeRange</a><br />A <a href="T_DevCase_Core_DateAndTime_TimeRange">TimeRange</a> that represents the start time and end time range.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the current time in the source TimeSpan is in range between the specified start time and end time range, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TimeSpan. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim input As TimeSpan = TimeSpan.Parse("00:00:00")
dim range as New TimeRange(TimeSpan.Parse("0.23:59:59"), TimeSpan.Parse("1.00:00:01"))

Dim result As Boolean = input.IsHourInRange(range)
Console.WriteLine(result) ' result = True
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TimeSpan_TimeSpanExtensions">TimeSpanExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_TimeSpan_TimeSpanExtensions_IsHourInRange">IsHourInRange Overload</a><br /><a href="N_DevCase_Core_Extensions_TimeSpan">DevCase.Core.Extensions.TimeSpan Namespace</a><br />