# ArrayExtensions.FillBounds(*T*) Method 
 

Fills the indices (or columns) of the specified index bound (or row) of the source array, using the given collection of elements.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void FillBounds<T>(
	this ref T[,] sender,
	int boundIndex,
	T[] array
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub FillBounds(Of T) ( 
	ByRef sender As T(,),
	boundIndex As Integer,
	array As T()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As T(,)
Dim boundIndex As Integer
Dim array As T()

sender.FillBounds(boundIndex, array)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void FillBounds(
	array<T,2>^% sender, 
	int boundIndex, 
	array<T>^ array
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FillBounds : 
        sender : 'T[,] byref * 
        boundIndex : int * 
        array : 'T[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: *T*[,]<br />The source array.</dd><dt>boundIndex</dt><dd>Type: System.Int32<br />The bound index (or row) of the first dimension in the source array.</dd><dt>array</dt><dd>Type: *T*[]<br />\[Missing <param name="array"/> documentation for "M:DevCase.Core.Extensions.Array.ArrayExtensions.FillBounds``1(``0[0:,0:]@,System.Int32,``0[])"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The <a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a> of the source array.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IndexOutOfRangeException</td><td>The specified 'boundIndex' value is greater than the bounds of the first dimension in the source array. or The amount of elements in 'collection' is greater than the bounds of the second dimension in the source array.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "0-1-2-3-4-5-6-7-8-9"
Dim arr2D(0, 9) As String
arr2D.FillBounds(0, str.Split({"-"c}, StringSplitOptions.RemoveEmptyEntries))

For i As Integer = 0 To (arr2D.GetLength(1) - 1)
    Console.WriteLine(arr2D(0, i))
Next i
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />