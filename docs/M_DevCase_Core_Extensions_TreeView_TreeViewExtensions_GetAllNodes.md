# TreeViewExtensions.GetAllNodes Method 
 

Gets all the nodes and all its child nodes in the source TreeView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static List<TreeNode> GetAllNodes(
	this TreeView sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetAllNodes ( 
	sender As TreeView
) As List(Of TreeNode)
```

**VB Usage**<br />
``` VB Usage
Dim sender As TreeView
Dim returnValue As List(Of TreeNode)

returnValue = sender.GetAllNodes()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static List<TreeNode^>^ GetAllNodes(
	TreeView^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetAllNodes : 
        sender : TreeView -> List<TreeNode> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.TreeView<br />The source TreeView.</dd></dl>

#### Return Value
Type: List(TreeNode)<br />A List(T) containing all the parent nodes and all its child nodes.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TreeView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
Credits to: <a href="http://stackoverflow.com/a/32962044/1248295" target="_blank">http://stackoverflow.com/a/32962044/1248295</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim nodeList As List(Of TreeNode) = Me.TreeView1.GetAllNodes()

For Each node As TreeNode In nodeList
    ' ...
Next node
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TreeView_TreeViewExtensions">TreeViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView Namespace</a><br />