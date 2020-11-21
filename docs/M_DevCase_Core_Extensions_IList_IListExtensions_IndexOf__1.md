# IListExtensions.IndexOf(*T*) Method 
 

Determines the index of a specific item in the IList(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IList">DevCase.Core.Extensions.IList</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int IndexOf<T>(
	this IList<T> sender,
	Func<T, bool> predicate
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IndexOf(Of T) ( 
	sender As IList(Of T),
	predicate As Func(Of T, Boolean)
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As IList(Of T)
Dim predicate As Func(Of T, Boolean)
Dim returnValue As Integer

returnValue = sender.IndexOf(predicate)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static int IndexOf(
	IList<T>^ sender, 
	Func<T, bool>^ predicate
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IndexOf : 
        sender : IList<'T> * 
        predicate : Func<'T, bool> -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IList(*T*)<br />The source IList(T).</dd><dt>predicate</dt><dd>Type: System.Func(*T*, Boolean)<br />A function to test each element for a condition..</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: Int32<br />The index of item if found in the list; otherwise, `-1`.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IList(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IList_IListExtensions">IListExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IList">DevCase.Core.Extensions.IList Namespace</a><br />