# TypeExtensions.GetAllDerivedTypes Method (Type)
 

Gets all the types that inherits from the source Type within the Assembly in which the source Type is defined.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<Type> GetAllDerivedTypes(
	this Type type
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetAllDerivedTypes ( 
	type As Type
) As IEnumerable(Of Type)
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim returnValue As IEnumerable(Of Type)

returnValue = type.GetAllDerivedTypes()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<Type^>^ GetAllDerivedTypes(
	Type^ type
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetAllDerivedTypes : 
        type : Type -> IEnumerable<Type> 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />The source Type.</dd></dl>

#### Return Value
Type: IEnumerable(Type)<br />All the types that inherits from the source Type within the loaded assembly in which the source Type is defined; or a null reference (`Nothing` in Visual Basic) if there is no Type that inherits from the source Type.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Type. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mainType As Type = GetType(Control)
Dim derivedTypes As IEnumerable(Of Type) = GetAllDerivedTypes(mainType)

Console.WriteLine(String.Join(Environment.NewLine, derivedTypes))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Type_TypeExtensions">TypeExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Type_TypeExtensions_GetAllDerivedTypes">GetAllDerivedTypes Overload</a><br /><a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type Namespace</a><br />