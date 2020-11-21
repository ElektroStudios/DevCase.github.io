# ArrayExtensions.FindIndex(*T*) Method (*T*[,], Predicate(*T*))
 

Searches for an element in the source three-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its first occurrence.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int[] FindIndex<T>(
	this T[,,] array,
	Predicate<T> match
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindIndex(Of T) ( 
	array As T(,,),
	match As Predicate(Of T)
) As Integer()
```

**VB Usage**<br />
``` VB Usage
Dim array As T(,,)
Dim match As Predicate(Of T)
Dim returnValue As Integer()

returnValue = array.FindIndex(match)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static array<int>^ FindIndex(
	array<T,3>^ array, 
	Predicate<T>^ match
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindIndex : 
        array : 'T[,,] * 
        match : Predicate<'T> -> int[] 

```


#### Parameters
&nbsp;<dl><dt>array</dt><dd>Type: *T*[,]<br />The source three-dimensional array.</dd><dt>match</dt><dd>Type: System.Predicate(*T*)<br />The Predicate(T) that defines the conditions of the element to search for.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the object to find.</dd></dl>

#### Return Value
Type: Int32[]<br />The index of the first occurrence for the specified object in the source array, or a null reference (`Nothing` in Visual Basic) if the object was not found in the array.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_FindIndex">FindIndex Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />