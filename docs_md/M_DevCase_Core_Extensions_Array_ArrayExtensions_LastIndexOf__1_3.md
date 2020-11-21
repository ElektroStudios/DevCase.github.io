# ArrayExtensions.LastIndexOf(*T*) Method (*T*[][], *T*)
 

Searches for the specified object in the source two-dimensional jagged array and returns the index of its last occurrence.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int[] LastIndexOf<T>(
	this T[][] array,
	T value
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function LastIndexOf(Of T) ( 
	array As T()(),
	value As T
) As Integer()
```

**VB Usage**<br />
``` VB Usage
Dim array As T()()
Dim value As T
Dim returnValue As Integer()

returnValue = array.LastIndexOf(value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static array<int>^ LastIndexOf(
	array<array<T>^>^ array, 
	T value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member LastIndexOf : 
        array : 'T[][] * 
        value : 'T -> int[] 

```


#### Parameters
&nbsp;<dl><dt>array</dt><dd>Type: *T*[][]<br />The source two-dimensional jagged array.</dd><dt>value</dt><dd>Type: *T*<br />The object to find.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the object to find.</dd></dl>

#### Return Value
Type: Int32[]<br />The index of the last occurrence for the specified object in the source jagged array, or a null reference (`Nothing` in Visual Basic) if the object was not found in the jagged array.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_LastIndexOf">LastIndexOf Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />