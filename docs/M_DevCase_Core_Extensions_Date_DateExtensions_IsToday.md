# DateExtensions.IsToday Method 
 

Determines whether the specified DateTime is today.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsToday(
	this DateTime sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsToday ( 
	sender As DateTime
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As DateTime
Dim returnValue As Boolean

returnValue = sender.IsToday()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsToday(
	DateTime sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsToday : 
        sender : DateTime -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.DateTime<br />The source DateTime.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified DateTime is today; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DateTime. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = Date.Today.IsToday()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Date_DateExtensions">DateExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date Namespace</a><br />