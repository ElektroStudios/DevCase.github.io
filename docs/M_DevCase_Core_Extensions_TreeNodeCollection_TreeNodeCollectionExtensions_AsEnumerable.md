# TreeNodeCollectionExtensions.AsEnumerable Method 
 

Enumerates all the TreeNode items in the specified specified TreeNodeCollection collection, and returns a IEnumerable(T) collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TreeNodeCollection">DevCase.Core.Extensions.TreeNodeCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<TreeNode> AsEnumerable(
	this TreeNodeCollection nodes,
	bool allChildren = false
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AsEnumerable ( 
	nodes As TreeNodeCollection,
	Optional allChildren As Boolean = false
) As IEnumerable(Of TreeNode)
```

**VB Usage**<br />
``` VB Usage
Dim nodes As TreeNodeCollection
Dim allChildren As Boolean
Dim returnValue As IEnumerable(Of TreeNode)

returnValue = nodes.AsEnumerable(allChildren)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static IEnumerable<TreeNode^>^ AsEnumerable(
	TreeNodeCollection^ nodes, 
	bool allChildren = false
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member AsEnumerable : 
        nodes : TreeNodeCollection * 
        ?allChildren : bool 
(* Defaults:
        let _allChildren = defaultArg allChildren false
*)
-> IEnumerable<TreeNode> 

```


#### Parameters
&nbsp;<dl><dt>nodes</dt><dd>Type: System.Windows.Forms.TreeNodeCollection<br />The source TreeNodeCollection collection.</dd><dt>allChildren (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), also includes child nodes of all child nodes.</dd></dl>

#### Return Value
Type: IEnumerable(TreeNode)<br />The resulting IEnumerable(T) collection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TreeNodeCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TreeNodeCollection_TreeNodeCollectionExtensions">TreeNodeCollectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TreeNodeCollection">DevCase.Core.Extensions.TreeNodeCollection Namespace</a><br />