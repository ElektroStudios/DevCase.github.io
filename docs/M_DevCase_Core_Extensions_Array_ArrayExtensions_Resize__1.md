# ArrayExtensions.Resize(*T*) Method 
 

Resizes the number of elements of the source collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T[] Resize<T>(
	this T[] sender,
	int newSize
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Resize(Of T) ( 
	sender As T(),
	newSize As Integer
) As T()
```

**VB Usage**<br />
``` VB Usage
Dim sender As T()
Dim newSize As Integer
Dim returnValue As T()

returnValue = sender.Resize(newSize)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static array<T>^ Resize(
	array<T>^ sender, 
	int newSize
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Resize : 
        sender : 'T[] * 
        newSize : int -> 'T[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: *T*[]<br />The source Array.</dd><dt>newSize</dt><dd>Type: System.Int32<br />The new size.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The array Type.</dd></dl>

#### Return Value
Type: *T*[]<br />The resized Array.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>newSize;Value greater than 0 is required.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myArray(50) As Integer
Console.WriteLine(String.Format("{0,-12}: {1}", "Initial Size", myArray.Length))

myArray = myArray.Resize(myArray.Length - 51)
Console.WriteLine(String.Format("{0,-12}: {1}", "New Size", myArray.Length))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />