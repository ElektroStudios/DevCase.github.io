# ScreenRegionSelector.RegionSelected Event
 

Occurs when a region is selected.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<RegionSelectedEventArgs> RegionSelected
```

**VB**<br />
``` VB
Public Event RegionSelected As EventHandler(Of RegionSelectedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ScreenRegionSelector
Dim handler As EventHandler(Of RegionSelectedEventArgs)

AddHandler instance.RegionSelected, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<RegionSelectedEventArgs^>^ RegionSelected {
	void add (EventHandler<RegionSelectedEventArgs^>^ value);
	void remove (EventHandler<RegionSelectedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member RegionSelected : IEvent<EventHandler<RegionSelectedEventArgs>,
    RegionSelectedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Imaging_Eventing_RegionSelectedEventArgs">RegionSelectedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ScreenRegionSelector">ScreenRegionSelector Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />