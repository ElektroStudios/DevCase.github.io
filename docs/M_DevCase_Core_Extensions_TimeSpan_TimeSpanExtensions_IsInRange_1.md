# TimeSpanExtensions.IsInRange Method (TimeSpan, TimeSpan, TimeSpan)
 

Determine whether the current time (days, hours, minutes, seconds and milliseconds) in the source TimeSpan is in range between the specified start time and end time range.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TimeSpan">DevCase.Core.Extensions.TimeSpan</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsInRange(
	this TimeSpan sender,
	TimeSpan start,
	TimeSpan end
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsInRange ( 
	sender As TimeSpan,
	start As TimeSpan,
	end As TimeSpan
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As TimeSpan
Dim start As TimeSpan
Dim end As TimeSpan
Dim returnValue As Boolean

returnValue = sender.IsInRange(start, 
	end)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsInRange(
	TimeSpan sender, 
	TimeSpan start, 
	TimeSpan end
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsInRange : 
        sender : TimeSpan * 
        start : TimeSpan * 
        end : TimeSpan -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.TimeSpan<br />The source TimeSpan.</dd><dt>start</dt><dd>Type: System.TimeSpan<br />A TimeSpan that represents the start time.</dd><dt>end</dt><dd>Type: System.TimeSpan<br />\[Missing <param name="end"/> documentation for "M:DevCase.Core.Extensions.TimeSpan.TimeSpanExtensions.IsInRange(System.TimeSpan,System.TimeSpan,System.TimeSpan)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the current time in the source TimeSpan is in range between the specified start time and end time range, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TimeSpan. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim input As TimeSpan = TimeSpan.Parse("1.00:00:00")
Dim start As TimeSpan = TimeSpan.Parse("0.23:59:59")
Dim [end] As TimeSpan = TimeSpan.Parse("1.00:00:01")

Dim result As Boolean = input.IsInRange(start, [end])
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TimeSpan_TimeSpanExtensions">TimeSpanExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_TimeSpan_TimeSpanExtensions_IsInRange">IsInRange Overload</a><br /><a href="N_DevCase_Core_Extensions_TimeSpan">DevCase.Core.Extensions.TimeSpan Namespace</a><br />