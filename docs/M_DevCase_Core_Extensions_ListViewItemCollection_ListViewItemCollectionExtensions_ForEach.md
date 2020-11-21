# ListViewItemCollectionExtensions.ForEach Method 
 

Performs the specified action on each item of the specified ListView.ListViewItemCollection collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListViewItemCollection">DevCase.Core.Extensions.ListViewItemCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ForEach(
	this ListView.ListViewItemCollection collection,
	Action<ListViewItem> action
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Sub ForEach ( 
	collection As ListView.ListViewItemCollection,
	action As Action(Of ListViewItem)
)
```

**VB Usage**<br />
``` VB Usage
Dim collection As ListView.ListViewItemCollection
Dim action As Action(Of ListViewItem)

collection.ForEach(action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static void ForEach(
	ListView.ListViewItemCollection^ collection, 
	Action<ListViewItem^>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ForEach : 
        collection : ListView.ListViewItemCollection * 
        action : Action<ListViewItem> -> unit 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Windows.Forms.ListView.ListViewItemCollection<br />The source ListView.ListViewItemCollection.</dd><dt>action</dt><dd>Type: System.Action(ListViewItem)<br />The action to perform on each item of the source collection.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView.ListViewItemCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListViewItemCollection_ListViewItemCollectionExtensions">ListViewItemCollectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListViewItemCollection">DevCase.Core.Extensions.ListViewItemCollection Namespace</a><br />