# DateExtensions.DaysInMonth Method 
 

Returns the number of days in the month for the date represented by the specified DateTime.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int DaysInMonth(
	this DateTime sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DaysInMonth ( 
	sender As DateTime
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As DateTime
Dim returnValue As Integer

returnValue = sender.DaysInMonth()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int DaysInMonth(
	DateTime sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DaysInMonth : 
        sender : DateTime -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.DateTime<br />The source DateTime.</dd></dl>

#### Return Value
Type: Int32<br />The number of days in the month for the date represented by the specified DateTime.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DateTime. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim days As Integer = Date.Today.DaysInMonth()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Date_DateExtensions">DateExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date Namespace</a><br />