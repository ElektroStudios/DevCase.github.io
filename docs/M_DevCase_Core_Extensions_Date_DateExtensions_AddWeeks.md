# DateExtensions.AddWeeks Method 
 

Returns a new DateTime that adds the specified number of weeks to the value of this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DateTime AddWeeks(
	this DateTime sender,
	double value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AddWeeks ( 
	sender As DateTime,
	value As Double
) As DateTime
```

**VB Usage**<br />
``` VB Usage
Dim sender As DateTime
Dim value As Double
Dim returnValue As DateTime

returnValue = sender.AddWeeks(value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DateTime AddWeeks(
	DateTime sender, 
	double value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddWeeks : 
        sender : DateTime * 
        value : float -> DateTime 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.DateTime<br />A valid DateTime instance.</dd><dt>value</dt><dd>Type: System.Double<br />A number of whole and fractional weeks. 

 The *value* parameter can be negative or positive.</dd></dl>

#### Return Value
Type: DateTime<br />A DateTime whose value is the sum of the date and time represented by this instance and the number of weeks represented by *value*.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DateTime. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim day As Date = Date.Today.AddWeeks(1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Date_DateExtensions">DateExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date Namespace</a><br />