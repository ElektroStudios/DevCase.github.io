# ArrayExtensions.Find(*T*) Method (*T*[][], Predicate(*T*))
 

Searches for an element in the source two-dimensional jagged array that matches the conditions defined by the specified predicate, and returns its first occurrence.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T Find<T>(
	this T[][] array,
	Predicate<T> match
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Find(Of T) ( 
	array As T()(),
	match As Predicate(Of T)
) As T
```

**VB Usage**<br />
``` VB Usage
Dim array As T()()
Dim match As Predicate(Of T)
Dim returnValue As T

returnValue = array.Find(match)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T Find(
	array<array<T>^>^ array, 
	Predicate<T>^ match
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Find : 
        array : 'T[][] * 
        match : Predicate<'T> -> 'T 

```


#### Parameters
&nbsp;<dl><dt>array</dt><dd>Type: *T*[][]<br />The source two-dimensional jagged array.</dd><dt>match</dt><dd>Type: System.Predicate(*T*)<br />The Predicate(T) that defines the conditions of the element to search for.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the object to find.</dd></dl>

#### Return Value
Type: *T*<br />The first occurrence for the specified object in the source jagged array, or a null reference (`Nothing` in Visual Basic) if the object was not found in the jagged array.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_Find">Find Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />