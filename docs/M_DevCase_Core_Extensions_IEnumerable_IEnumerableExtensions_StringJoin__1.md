# IEnumerableExtensions.StringJoin(*T*) Method 
 

Joins multiple IEnumerable(T) at once into a single string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string StringJoin<T>(
	this IEnumerable<T>[] sender,
	string separator
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function StringJoin(Of T) ( 
	sender As IEnumerable(Of T)(),
	separator As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)()
Dim separator As String
Dim returnValue As String

returnValue = sender.StringJoin(separator)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static String^ StringJoin(
	array<IEnumerable<T>^>^ sender, 
	String^ separator
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member StringJoin : 
        sender : IEnumerable<'T>[] * 
        separator : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)[]<br />The source collections.</dd><dt>separator</dt><dd>Type: System.String<br />The string to use as a separator.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: String<br />String.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim col1 As IEnumerable(Of Integer) = {1, 2, 3}
Dim col2 As IEnumerable(Of Integer) = {4, 5, 6}
Dim col3 As IEnumerable(Of Integer) = {7, 8, 9}
Debug.WriteLine({col1, col2, col3}.StringJoin(", ")))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />