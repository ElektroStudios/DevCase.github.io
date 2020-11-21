# DateExtensions.LastDayOfWeek Method (DateTime)
 

Returns a DateTime which represents the last day of the week of the date represented by the specified DateTime.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DateTime LastDayOfWeek(
	this DateTime sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function LastDayOfWeek ( 
	sender As DateTime
) As DateTime
```

**VB Usage**<br />
``` VB Usage
Dim sender As DateTime
Dim returnValue As DateTime

returnValue = sender.LastDayOfWeek()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DateTime LastDayOfWeek(
	DateTime sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member LastDayOfWeek : 
        sender : DateTime -> DateTime 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.DateTime<br />The source DateTime.</dd></dl>

#### Return Value
Type: DateTime<br />A DateTime which represents the last day of the week of the date represented by the specified DateTime.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DateTime. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dt As Date = Date.Today.LastDayOfWeek()
Dim day As Integer = dt.Day
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Date_DateExtensions">DateExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Date_DateExtensions_LastDayOfWeek">LastDayOfWeek Overload</a><br /><a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date Namespace</a><br />