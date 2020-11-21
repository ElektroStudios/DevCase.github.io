# NullableExtensions.ConvertToNonNullable(*T*) Method 
 

Converts an Array of Nullable values to an Array of non-nullable values of the same <a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Nullable">DevCase.Core.Extensions.Nullable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T[] ConvertToNonNullable<T>(
	this Nullable<T>[] source,
	T defaultIfNull = null
)
where T : struct, new()

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ConvertToNonNullable(Of T As {Structure, New}) ( 
	source As Nullable(Of T)(),
	Optional defaultIfNull As T = Nothing
) As T()
```

**VB Usage**<br />
``` VB Usage
Dim source As Nullable(Of T)()
Dim defaultIfNull As T
Dim returnValue As T()

returnValue = source.ConvertToNonNullable(defaultIfNull)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : value class, gcnew()
static array<T>^ ConvertToNonNullable(
	array<Nullable<T>>^ source, 
	T defaultIfNull = nullptr
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ConvertToNonNullable : 
        source : Nullable<'T>[] * 
        ?defaultIfNull : 'T 
(* Defaults:
        let _defaultIfNull = defaultArg defaultIfNull null
*)
-> 'T[]  when 'T : struct, new()

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Nullable(*T*)[]<br />The source Nullable value.</dd><dt>defaultIfNull (Optional)</dt><dd>Type: *T*<br />The default value to use if Nullable value is null (a null reference (`Nothing` in Visual Basic)). 

 Default value is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the source Nullable value.</dd></dl>

#### Return Value
Type: *T*[]<br />The resulting Array of non-nullable values.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim nullableArray As Nullable(Of Byte)() = {0, Nothing, 1}
Dim nonNullableArray As Byte() = nullableArray.ConvertToNonNullable(defaultIfNull:=0)
Console.WriteLine(String.Join(", ", nonNullableArray))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Nullable_NullableExtensions">NullableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Nullable">DevCase.Core.Extensions.Nullable Namespace</a><br />