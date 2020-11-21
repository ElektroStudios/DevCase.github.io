# TreeViewExtensions.EnumerateAllNodes Method 
 

Enumerates all the nodes and all its child nodes in the source TreeView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<TreeNode> EnumerateAllNodes(
	this TreeView treeView
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function EnumerateAllNodes ( 
	treeView As TreeView
) As IEnumerable(Of TreeNode)
```

**VB Usage**<br />
``` VB Usage
Dim treeView As TreeView
Dim returnValue As IEnumerable(Of TreeNode)

returnValue = treeView.EnumerateAllNodes()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static IEnumerable<TreeNode^>^ EnumerateAllNodes(
	TreeView^ treeView
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member EnumerateAllNodes : 
        treeView : TreeView -> IEnumerable<TreeNode> 

```


#### Parameters
&nbsp;<dl><dt>treeView</dt><dd>Type: System.Windows.Forms.TreeView<br />The source TreeView.</dd></dl>

#### Return Value
Type: IEnumerable(TreeNode)<br />An IEnumerable(T) containing all TreeNode instances in the source TreeView.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TreeView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TreeView_TreeViewExtensions">TreeViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TreeView">DevCase.Core.Extensions.TreeView Namespace</a><br />