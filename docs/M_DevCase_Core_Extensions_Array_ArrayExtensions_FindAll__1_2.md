# ArrayExtensions.FindAll(*T*) Method (*T*[,], Predicate(*T*))
 

Searches for all the elements in the source two-dimensional array that matches the conditions defined by the specified predicate.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<T> FindAll<T>(
	this T[,] array,
	Predicate<T> match
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindAll(Of T) ( 
	array As T(,),
	match As Predicate(Of T)
) As IEnumerable(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim array As T(,)
Dim match As Predicate(Of T)
Dim returnValue As IEnumerable(Of T)

returnValue = array.FindAll(match)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static IEnumerable<T>^ FindAll(
	array<T,2>^ array, 
	Predicate<T>^ match
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindAll : 
        array : 'T[,] * 
        match : Predicate<'T> -> IEnumerable<'T> 

```


#### Parameters
&nbsp;<dl><dt>array</dt><dd>Type: *T*[,]<br />The source two-dimensional array.</dd><dt>match</dt><dd>Type: System.Predicate(*T*)<br />The Predicate(T) that defines the conditions of the element to search for.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the object to find.</dd></dl>

#### Return Value
Type: IEnumerable(*T*)<br />All the elements in the source two-dimensional array that matches the conditions defined by the specified predicate.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_FindAll">FindAll Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />