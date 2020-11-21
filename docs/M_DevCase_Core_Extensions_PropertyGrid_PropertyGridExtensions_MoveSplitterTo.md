# PropertyGridExtensions.MoveSplitterTo Method 
 

Moves the splitter control of the source the PropertyGrid to adjust the columns width.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_PropertyGrid">DevCase.Core.Extensions.PropertyGrid</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void MoveSplitterTo(
	this PropertyGrid propGrid,
	int width
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub MoveSplitterTo ( 
	propGrid As PropertyGrid,
	width As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim propGrid As PropertyGrid
Dim width As Integer

propGrid.MoveSplitterTo(width)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void MoveSplitterTo(
	PropertyGrid^ propGrid, 
	int width
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MoveSplitterTo : 
        propGrid : PropertyGrid * 
        width : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>propGrid</dt><dd>Type: System.Windows.Forms.PropertyGrid<br />The source PropertyGrid.</dd><dt>width</dt><dd>Type: System.Int32<br />The desired width.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type PropertyGrid. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_PropertyGrid_PropertyGridExtensions">PropertyGridExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_PropertyGrid">DevCase.Core.Extensions.PropertyGrid Namespace</a><br />