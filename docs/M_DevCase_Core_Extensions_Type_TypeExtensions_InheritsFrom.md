# TypeExtensions.InheritsFrom Method 
 

Determines whether the specified type inherits from the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool InheritsFrom(
	this Type sender,
	Type baseType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function InheritsFrom ( 
	sender As Type,
	baseType As Type
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Type
Dim baseType As Type
Dim returnValue As Boolean

returnValue = sender.InheritsFrom(baseType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool InheritsFrom(
	Type^ sender, 
	Type^ baseType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member InheritsFrom : 
        sender : Type * 
        baseType : Type -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Type<br />The type to test.</dd><dt>baseType</dt><dd>Type: System.Type<br />The base type to check.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source type inherits from the specified Type; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Type. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = GetType(Control).InheritsFrom(GetType(Component))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Type_TypeExtensions">TypeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type Namespace</a><br />