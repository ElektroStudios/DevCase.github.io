# DevStarRate.ValueChanged Event
 

Occurs when the star rating value changes.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<StarRateValueChangedEventArgs> ValueChanged
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event ValueChanged As EventHandler(Of StarRateValueChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevStarRate
Dim handler As EventHandler(Of StarRateValueChangedEventArgs)

AddHandler instance.ValueChanged, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<StarRateValueChangedEventArgs^>^ ValueChanged {
	void add (EventHandler<StarRateValueChangedEventArgs^>^ value);
	void remove (EventHandler<StarRateValueChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member ValueChanged : IEvent<EventHandler<StarRateValueChangedEventArgs>,
    StarRateValueChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Controls_Eventing_StarRateValueChangedEventArgs">StarRateValueChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevStarRate">DevStarRate Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />