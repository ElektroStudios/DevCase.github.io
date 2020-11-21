# ListViewItemCollectionExtensions.AsEnumerable Method 
 

Enumerates all the ListViewItem items in the source ListView.ListViewItemCollection collection, and returns a IEnumerable(T) collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListViewItemCollection">DevCase.Core.Extensions.ListViewItemCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<ListViewItem> AsEnumerable(
	this ListView.ListViewItemCollection collection
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AsEnumerable ( 
	collection As ListView.ListViewItemCollection
) As IEnumerable(Of ListViewItem)
```

**VB Usage**<br />
``` VB Usage
Dim collection As ListView.ListViewItemCollection
Dim returnValue As IEnumerable(Of ListViewItem)

returnValue = collection.AsEnumerable()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static IEnumerable<ListViewItem^>^ AsEnumerable(
	ListView.ListViewItemCollection^ collection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member AsEnumerable : 
        collection : ListView.ListViewItemCollection -> IEnumerable<ListViewItem> 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Windows.Forms.ListView.ListViewItemCollection<br />The source ListView.ListViewItemCollection collection.</dd></dl>

#### Return Value
Type: IEnumerable(ListViewItem)<br />The resulting IEnumerable(T) collection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView.ListViewItemCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListViewItemCollection_ListViewItemCollectionExtensions">ListViewItemCollectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListViewItemCollection">DevCase.Core.Extensions.ListViewItemCollection Namespace</a><br />