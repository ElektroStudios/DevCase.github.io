# NullableExtensions.ConvertTo(*TSource*, *TTarget*) Method 
 

Converts a source Nullable value to the target Nullable value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Nullable">DevCase.Core.Extensions.Nullable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Nullable<TTarget> ConvertTo<TSource, TTarget>(
	this Nullable<TSource> source,
	Func<TSource, TTarget> converter
)
where TSource : struct, new()
where TTarget : struct, new()

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ConvertTo(Of TSource As {Structure, New}, TTarget As {Structure, New}) ( 
	source As Nullable(Of TSource),
	converter As Func(Of TSource, TTarget)
) As Nullable(Of TTarget)
```

**VB Usage**<br />
``` VB Usage
Dim source As Nullable(Of TSource)
Dim converter As Func(Of TSource, TTarget)
Dim returnValue As Nullable(Of TTarget)

returnValue = source.ConvertTo(converter)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename TSource, typename TTarget>
where TSource : value class, gcnew()
where TTarget : value class, gcnew()
static Nullable<TTarget> ConvertTo(
	Nullable<TSource> source, 
	Func<TSource, TTarget>^ converter
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ConvertTo : 
        source : Nullable<'TSource> * 
        converter : Func<'TSource, 'TTarget> -> Nullable<'TTarget>  when 'TSource : struct, new() when 'TTarget : struct, new()

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Nullable(*TSource*)<br />The source Nullable value.</dd><dt>converter</dt><dd>Type: System.Func(*TSource*, *TTarget*)<br />A function that will serve to convert from the source Nullable value to the target Nullable value.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TSource</dt><dd>The type of the source Nullable value.</dd><dt>TTarget</dt><dd>The type of the target Nullable value.</dd></dl>

#### Return Value
Type: Nullable(*TTarget*)<br />The resulting Nullable value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Nullable(*TSource*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim nullableByte As Nullable(Of Byte) = New Byte?(255)
Dim nullableInt32 As Nullable(Of Integer) = nullableByte.ConvertTo(Function(ByVal value As Nullable(Of Byte)) Convert.ToInt32(value))
Console.WriteLine(nullableInt32)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Nullable_NullableExtensions">NullableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Nullable">DevCase.Core.Extensions.Nullable Namespace</a><br />