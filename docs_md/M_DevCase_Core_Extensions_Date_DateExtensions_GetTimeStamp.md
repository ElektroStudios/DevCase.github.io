# DateExtensions.GetTimeStamp Method 
 

Gets the time stamp of the source specified DateTime, in `ISO 8601` format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetTimeStamp(
	this DateTime sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetTimeStamp ( 
	sender As DateTime
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As DateTime
Dim returnValue As String

returnValue = sender.GetTimeStamp()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetTimeStamp(
	DateTime sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetTimeStamp : 
        sender : DateTime -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.DateTime<br />\[Missing <param name="sender"/> documentation for "M:DevCase.Core.Extensions.Date.DateExtensions.GetTimeStamp(System.DateTime)"\]</dd></dl>

#### Return Value
Type: String<br />The resulting time stamp.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DateTime. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
<a href="http://en.wikipedia.org/wiki/ISO_8601" target="_blank">http://en.wikipedia.org/wiki/ISO_8601</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Date_DateExtensions">DateExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Date">DevCase.Core.Extensions.Date Namespace</a><br />