# DevListView.ItemRemoved Event
 

Occurs when a item is removed from the items collection of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<ListViewItemRemovedEventArgs> ItemRemoved
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event ItemRemoved As EventHandler(Of ListViewItemRemovedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListView
Dim handler As EventHandler(Of ListViewItemRemovedEventArgs)

AddHandler instance.ItemRemoved, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<ListViewItemRemovedEventArgs^>^ ItemRemoved {
	void add (EventHandler<ListViewItemRemovedEventArgs^>^ value);
	void remove (EventHandler<ListViewItemRemovedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member ItemRemoved : IEvent<EventHandler<ListViewItemRemovedEventArgs>,
    ListViewItemRemovedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Controls_Eventing_ListViewItemRemovedEventArgs">ListViewItemRemovedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListView">DevListView Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />