# TypeExtensions.GetAllBaseTypes Method 
 

Gets the Type inheritance hierarchy of the the source Type, that is, the type from which the source Type directly inherits, and the types from which their inherited types inherits.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<Type> GetAllBaseTypes(
	this Type type
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetAllBaseTypes ( 
	type As Type
) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim returnValue As IEnumerable(Of Type)

returnValue = type.GetAllBaseTypes()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<Type^>^ GetAllBaseTypes(
	Type^ type
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetAllBaseTypes : 
        type : Type -> IEnumerable<Type> 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source Type.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />The type from which the source Type directly inherits, and the types from which the inherited types inherits; or a null reference (`Nothing` in Visual Basic) if the source Type represents the Object class or an interface.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Type. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mainType As Type = GetType(Form)
Dim types As IEnumerable(Of Type) = GetAllBaseTypes(mainType)

Dim sb As New StringBuilder()
sb.AppendLine($"Type inheritance hierarchy of '{mainType.FullName}':")
sb.AppendLine()

For i As Integer = 0 To (types.Count - 1)
    sb.AppendLine($"{String.Concat(Enumerable.Repeat(" "c, (i * 4)))}{types(i).FullName}")
Next i

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Type_TypeExtensions">TypeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type Namespace</a><br />