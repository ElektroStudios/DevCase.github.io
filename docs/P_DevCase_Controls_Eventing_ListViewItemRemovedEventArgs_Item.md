# ListViewItemRemovedEventArgs.Item Property 
 

Gets the removed item.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override ListViewItem Item { get; }
```

**VB**<br />
``` VB
Public Overrides ReadOnly Property Item As ListViewItem
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListViewItemRemovedEventArgs
Dim value As ListViewItem

value = instance.Item

```

**C++**<br />
``` C++
public:
virtual property ListViewItem^ Item {
	ListViewItem^ get () override;
}
```

**F#**<br />
``` F#
abstract Item : ListViewItem with get
override Item : ListViewItem with get
```


#### Property Value
Type: ListViewItem<br />The removed item.

## See Also


#### Reference
<a href="T_DevCase_Controls_Eventing_ListViewItemRemovedEventArgs">ListViewItemRemovedEventArgs Class</a><br /><a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing Namespace</a><br />