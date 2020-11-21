# ListViewItemAddedEventArgs.NewItem Property 
 

Gets the value.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override ListViewItem NewItem { get; }
```

**VB**<br />
``` VB
Public Overrides ReadOnly Property NewItem As ListViewItem
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListViewItemAddedEventArgs
Dim value As ListViewItem

value = instance.NewItem

```

**C++**<br />
``` C++
public:
virtual property ListViewItem^ NewItem {
	ListViewItem^ get () override;
}
```

**F#**<br />
``` F#
abstract NewItem : ListViewItem with get
override NewItem : ListViewItem with get
```


#### Property Value
Type: ListViewItem<br />The value.

## See Also


#### Reference
<a href="T_DevCase_Controls_Eventing_ListViewItemAddedEventArgs">ListViewItemAddedEventArgs Class</a><br /><a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing Namespace</a><br />