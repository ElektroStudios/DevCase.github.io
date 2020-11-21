# IEnumerableExtensions.SplitIntoNumberOfElements(*T*) Method (IEnumerable(*T*), Int32, Boolean, *T*)
 

Splits the source IEnumerable(T) into secuences with the specified amount of elements.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<IEnumerable<T>> SplitIntoNumberOfElements<T>(
	this IEnumerable<T> sender,
	int amount,
	bool fillEmpty,
	T valueToFill = null
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SplitIntoNumberOfElements(Of T) ( 
	sender As IEnumerable(Of T),
	amount As Integer,
	fillEmpty As Boolean,
	Optional valueToFill As T = Nothing
) As IEnumerable(Of IEnumerable(Of T))
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim amount As Integer
Dim fillEmpty As Boolean
Dim valueToFill As T
Dim returnValue As IEnumerable(Of IEnumerable(Of T))

returnValue = sender.SplitIntoNumberOfElements(amount, 
	fillEmpty, valueToFill)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static IEnumerable<IEnumerable<T>^>^ SplitIntoNumberOfElements(
	IEnumerable<T>^ sender, 
	int amount, 
	bool fillEmpty, 
	T valueToFill = nullptr
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SplitIntoNumberOfElements : 
        sender : IEnumerable<'T> * 
        amount : int * 
        fillEmpty : bool * 
        ?valueToFill : 'T 
(* Defaults:
        let _valueToFill = defaultArg valueToFill null
*)
-> IEnumerable<IEnumerable<'T>> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source collection.</dd><dt>amount</dt><dd>Type: System.Int32<br />The target amount of elements.</dd><dt>fillEmpty</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), generates empty elements to fill the last secuence's part amount.</dd><dt>valueToFill (Optional)</dt><dd>Type: *T*<br />An optional value used to fill the last secuence's part amount.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: IEnumerable(IEnumerable(*T*))<br />IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mainCol As IEnumerable(Of Integer) = {1, 2, 3, 4, 5, 6, 7, 8, 9}
Dim splittedCols As IEnumerable(Of IEnumerable(Of Integer)) = mainCol.SplitIntoNumberOfElements(amount:=4, fillEmpty:=True, valueToFill:=0)
splittedCols.ToList.ForEach(Sub(col As IEnumerable(Of Integer))
                                Debug.WriteLine(String.Join(", ", col))
                            End Sub)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoNumberOfElements">SplitIntoNumberOfElements Overload</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />