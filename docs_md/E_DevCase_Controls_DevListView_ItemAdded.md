# DevListView.ItemAdded Event
 

Occurs when a new item is added into the items collection of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<ListViewItemAddedEventArgs> ItemAdded
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event ItemAdded As EventHandler(Of ListViewItemAddedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListView
Dim handler As EventHandler(Of ListViewItemAddedEventArgs)

AddHandler instance.ItemAdded, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<ListViewItemAddedEventArgs^>^ ItemAdded {
	void add (EventHandler<ListViewItemAddedEventArgs^>^ value);
	void remove (EventHandler<ListViewItemAddedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member ItemAdded : IEvent<EventHandler<ListViewItemAddedEventArgs>,
    ListViewItemAddedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Controls_Eventing_ListViewItemAddedEventArgs">ListViewItemAddedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListView">DevListView Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />