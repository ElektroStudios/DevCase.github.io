# ObjectExtensions.ShallowCopy(*T*) Method 
 

Creates a shallow copy of the specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T ShallowCopy<T>(
	this T object
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ShallowCopy(Of T) ( 
	object As T
) As T
```

**VB Usage**<br />
``` VB Usage
Dim object As T
Dim returnValue As T

returnValue = object.ShallowCopy()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T ShallowCopy(
	T object
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ShallowCopy : 
        object : 'T -> 'T 

```


#### Parameters
&nbsp;<dl><dt>object</dt><dd>Type: *T*<br />\[Missing <param name="object"/> documentation for "M:DevCase.Core.Extensions.Object.ObjectExtensions.ShallowCopy``1(``0)"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />A shallow copy of the specified object.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object Namespace</a><br />