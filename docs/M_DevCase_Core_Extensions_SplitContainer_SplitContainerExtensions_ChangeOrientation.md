# SplitContainerExtensions.ChangeOrientation Method 
 

Changes the orientation of the source SplitContainer and assigns the 50% width for each SplitterPanel.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SplitContainer">DevCase.Core.Extensions.SplitContainer</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ChangeOrientation(
	this SplitContainer sender,
	Orientation newOrientation
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ChangeOrientation ( 
	sender As SplitContainer,
	newOrientation As Orientation
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As SplitContainer
Dim newOrientation As Orientation

sender.ChangeOrientation(newOrientation)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void ChangeOrientation(
	SplitContainer^ sender, 
	Orientation newOrientation
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ChangeOrientation : 
        sender : SplitContainer * 
        newOrientation : Orientation -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.SplitContainer<br />The source SplitContainer.</dd><dt>newOrientation</dt><dd>Type: System.Windows.Forms.Orientation<br />\[Missing <param name="newOrientation"/> documentation for "M:DevCase.Core.Extensions.SplitContainer.SplitContainerExtensions.ChangeOrientation(System.Windows.Forms.SplitContainer,System.Windows.Forms.Orientation)"\]</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SplitContainer. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SplitContainer_SplitContainerExtensions">SplitContainerExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SplitContainer">DevCase.Core.Extensions.SplitContainer Namespace</a><br />