# TypeExtensions.CreateInstance(*T*) Method (Type, Object[])
 

Creates an instance of the specified type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T CreateInstance<T>(
	this Type type,
	params Object[] parameters
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateInstance(Of T) ( 
	type As Type,
	ParamArray parameters As Object()
) As T
```

**VB Usage**<br />
``` VB Usage
Dim type As Type
Dim parameters As Object()
Dim returnValue As T

returnValue = type.CreateInstance(parameters)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T CreateInstance(
	Type^ type, 
	... array<Object^>^ parameters
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateInstance : 
        type : Type * 
        parameters : Object[] -> 'T 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: System.Type<br />\[Missing <param name="type"/> documentation for "M:DevCase.Core.Extensions.Type.TypeExtensions.CreateInstance``1(System.Type,System.Object[])"\]</dd><dt>parameters</dt><dd>Type: System.Object[]<br />Optional constructor parameters.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />The instanciated object.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Type. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim t As Type = GetType(Control)
Dim instance As Control = t.CreateInstance(Of Control)()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Type_TypeExtensions">TypeExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Type_TypeExtensions_CreateInstance">CreateInstance Overload</a><br /><a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type Namespace</a><br />