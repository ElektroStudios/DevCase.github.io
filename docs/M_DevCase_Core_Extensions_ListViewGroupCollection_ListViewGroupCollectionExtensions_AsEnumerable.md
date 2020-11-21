# ListViewGroupCollectionExtensions.AsEnumerable Method 
 

Enumerates all the ListViewGroup items in the source ListViewGroupCollection collection, and returns a IEnumerable(T) collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListViewGroupCollection">DevCase.Core.Extensions.ListViewGroupCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<ListViewGroup> AsEnumerable(
	this ListViewGroupCollection collection
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AsEnumerable ( 
	collection As ListViewGroupCollection
) As IEnumerable(Of ListViewGroup)
```

**VB Usage**<br />
``` VB Usage
Dim collection As ListViewGroupCollection
Dim returnValue As IEnumerable(Of ListViewGroup)

returnValue = collection.AsEnumerable()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static IEnumerable<ListViewGroup^>^ AsEnumerable(
	ListViewGroupCollection^ collection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member AsEnumerable : 
        collection : ListViewGroupCollection -> IEnumerable<ListViewGroup> 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Windows.Forms.ListViewGroupCollection<br />The source ListViewGroupCollection collection.</dd></dl>

#### Return Value
Type: IEnumerable(ListViewGroup)<br />The resulting IEnumerable(T) collection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListViewGroupCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListViewGroupCollection_ListViewGroupCollectionExtensions">ListViewGroupCollectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListViewGroupCollection">DevCase.Core.Extensions.ListViewGroupCollection Namespace</a><br />