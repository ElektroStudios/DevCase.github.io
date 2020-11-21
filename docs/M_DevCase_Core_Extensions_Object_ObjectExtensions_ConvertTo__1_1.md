# ObjectExtensions.ConvertTo(*T*) Method (Object, *T*)
 

Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T ConvertTo<T>(
	this Object object,
	T defaultValue
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ConvertTo(Of T) ( 
	object As Object,
	defaultValue As T
) As T
```

**VB Usage**<br />
``` VB Usage
Dim object As Object
Dim defaultValue As T
Dim returnValue As T

returnValue = object.ConvertTo(defaultValue)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T ConvertTo(
	Object^ object, 
	T defaultValue
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ConvertTo : 
        object : Object * 
        defaultValue : 'T -> 'T 

```


#### Parameters
&nbsp;<dl><dt>object</dt><dd>Type: System.Object<br />\[Missing <param name="object"/> documentation for "M:DevCase.Core.Extensions.Object.ObjectExtensions.ConvertTo``1(System.Object,``0)"\]</dd><dt>defaultValue</dt><dd>Type: *T*<br />The default value to return if the conversion fails.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />If the conversion fails, returns the resulting object of the specified target type. 

 If the conversion fails, returns the specified default value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Object. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As String = "1000000000000000000000000"
Dim obj As Integer = value.ConvertTo(Of Integer)(Integer.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo">ConvertTo Overload</a><br /><a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object Namespace</a><br />