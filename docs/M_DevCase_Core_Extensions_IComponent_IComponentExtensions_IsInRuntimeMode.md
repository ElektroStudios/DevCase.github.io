# IComponentExtensions.IsInRuntimeMode Method 
 

Determines whether the source IComponent is in runtime mode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IComponent">DevCase.Core.Extensions.IComponent</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsInRuntimeMode(
	this IComponent sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsInRuntimeMode ( 
	sender As IComponent
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As IComponent
Dim returnValue As Boolean

returnValue = sender.IsInRuntimeMode()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsInRuntimeMode(
	IComponent^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsInRuntimeMode : 
        sender : IComponent -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.ComponentModel.IComponent<br />The source IComponent.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source IComponent is in runtime mode; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IComponent. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ctrl As IComponent = New Label
Dim result As Boolean = ctrl.IsInRuntimeMode()
Debug.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IComponent_IComponentExtensions">IComponentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IComponent">DevCase.Core.Extensions.IComponent Namespace</a><br />