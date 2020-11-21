# TreeViewExtensions.SaveTreeState Method 
 

Saves the state of the source TreeView into a Dictionary(TKey, TValue) containing the hash code of each node and its expansion state.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Dictionary<int, bool> SaveTreeState(
	this TreeView sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SaveTreeState ( 
	sender As TreeView
) As Dictionary(Of Integer, Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim sender As TreeView
Dim returnValue As Dictionary(Of Integer, Boolean)

returnValue = sender.SaveTreeState()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Dictionary<int, bool>^ SaveTreeState(
	TreeView^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SaveTreeState : 
        sender : TreeView -> Dictionary<int, bool> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.TreeView<br />The source TreeView.</dd></dl>

#### Return Value
Type: Dictionary(Int32, Boolean)<br />A Dictionary(TKey, TValue) containing the hash code of each node and its expansion state.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TreeView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim saveState As Dictionary(Of Integer, Boolean) = Me.TreeView1.SaveTreeState()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TreeView_TreeViewExtensions">TreeViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView Namespace</a><br />