# StringExtensions.RemoveByLike Method 
 

Performs a String-Like pattern search on the source IEnumerable(T) and removes all the matches.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<string> RemoveByLike(
	this IEnumerable<string> sender,
	string likePattern,
	bool ignoreCase
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function RemoveByLike ( 
	sender As IEnumerable(Of String),
	likePattern As String,
	ignoreCase As Boolean
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of String)
Dim likePattern As String
Dim ignoreCase As Boolean
Dim returnValue As IEnumerable(Of String)

returnValue = sender.RemoveByLike(likePattern, 
	ignoreCase)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<String^>^ RemoveByLike(
	IEnumerable<String^>^ sender, 
	String^ likePattern, 
	bool ignoreCase
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveByLike : 
        sender : IEnumerable<string> * 
        likePattern : string * 
        ignoreCase : bool -> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source collections.</dd><dt>likePattern</dt><dd>Type: System.String<br />The pattern comparison to use with the `Like` operator.</dd><dt>ignoreCase</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), performs a non sensitive string-case comparison.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(String). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim col As IEnumerable(Of String) = {"Hello World", "a", "b", "c"}
Debug.WriteLine(String.Join(", ", col.RemoveByLike(likePattern:="*hello*", ignoreCase:=True)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />