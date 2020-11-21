# ObjectExtensions.IsDisposable Method 
 

Determines whether the specified object is disposable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsDisposable(
	this Object object
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsDisposable ( 
	object As Object
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim object As Object
Dim returnValue As Boolean

returnValue = object.IsDisposable()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsDisposable(
	Object^ object
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsDisposable : 
        object : Object -> bool 

```


#### Parameters
&nbsp;<dl><dt>object</dt><dd>Type: System.Object<br />\[Missing <param name="object"/> documentation for "M:DevCase.Core.Extensions.Object.ObjectExtensions.IsDisposable(System.Object)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified object is disposable; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Object. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = (New Process).IsDisposable()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Object">DevCase.Core.Extensions.Object Namespace</a><br />