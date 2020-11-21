# TreeNodeCollectionExtensions.AddFile Method (TreeNodeCollection, FileInfo)
 

Given the specified file, this function resolves its icon and adds a new tree node to the end of the source TreeNodeCollection collection. 

 This tree node contains the file name and its icon as image index.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TreeNodeCollection">DevCase.Core.Extensions.TreeNodeCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TreeNode AddFile(
	this TreeNodeCollection nodes,
	FileInfo file
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AddFile ( 
	nodes As TreeNodeCollection,
	file As FileInfo
) As TreeNode
```

**VB Usage**<br />
``` VB Usage
Dim nodes As TreeNodeCollection
Dim file As FileInfo
Dim returnValue As TreeNode

returnValue = nodes.AddFile(file)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static TreeNode^ AddFile(
	TreeNodeCollection^ nodes, 
	FileInfo^ file
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member AddFile : 
        nodes : TreeNodeCollection * 
        file : FileInfo -> TreeNode 

```


#### Parameters
&nbsp;<dl><dt>nodes</dt><dd>Type: System.Windows.Forms.TreeNodeCollection<br />The source TreeNodeCollection.</dd><dt>file</dt><dd>Type: System.IO.FileInfo<br />The file to add.</dd></dl>

#### Return Value
Type: TreeNode<br />The resulting TreeNode.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TreeNodeCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Me.TreeView1.ImageList = New ImageList With {.ImageSize = New Size(16, 16)}

Dim dir As New DirectoryInfo("C:\Windows\System32")
Me.TreeView1.Nodes.AddDirectory(dir)

Dim dirNodes As TreeNodeCollection = Me.TreeView1.Nodes(dir.FullName).Nodes

Me.TreeView1.BeginUpdate()
For Each fi As FileInfo In dir.EnumerateFiles()
    dirNodes.AddFile(fi)
Next fi
Me.TreeView1.EndUpdate()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TreeNodeCollection_TreeNodeCollectionExtensions">TreeNodeCollectionExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_TreeNodeCollection_TreeNodeCollectionExtensions_AddFile">AddFile Overload</a><br /><a href="N_DevCase_Core_Extensions_TreeNodeCollection">DevCase.Core.Extensions.TreeNodeCollection Namespace</a><br />