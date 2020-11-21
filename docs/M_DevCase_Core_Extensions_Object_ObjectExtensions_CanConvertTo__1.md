# ObjectExtensions.CanConvertTo(*T*) Method (Object)
 

Determines whether the source object can be converted to the specified target type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool CanConvertTo<T>(
	this Object object
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CanConvertTo(Of T) ( 
	object As Object
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim object As Object
Dim returnValue As Boolean

returnValue = object.CanConvertTo()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static bool CanConvertTo(
	Object^ object
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CanConvertTo : 
        object : Object -> bool 

```


#### Parameters
&nbsp;<dl><dt>object</dt><dd>Type: System.Object<br />\[Missing <param name="object"/> documentation for "M:DevCase.Core.Extensions.Object.ObjectExtensions.CanConvertTo``1(System.Object)"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source object can be converted to the specified target type; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Object. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = "Red".CanConvertTo(Of Color)()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo Overload</a><br /><a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object Namespace</a><br />