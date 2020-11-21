# TimeMeasurer.TimeUpdatedEventHandler Delegate
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate void TimeUpdatedEventHandler(
	Object sender,
	TimeMeasurerUpdatedEventArgs e
)
```

**VB**<br />
``` VB
Public Delegate Sub TimeUpdatedEventHandler ( 
	sender As Object,
	e As TimeMeasurerUpdatedEventArgs
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As New TimeUpdatedEventHandler(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate void TimeUpdatedEventHandler(
	Object^ sender, 
	TimeMeasurerUpdatedEventArgs^ e
)
```

**F#**<br />
``` F#
type TimeUpdatedEventHandler = 
    delegate of 
        sender : Object * 
        e : TimeMeasurerUpdatedEventArgs -> unit
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br /></dd><dt>e</dt><dd>Type: <a href="T_DevCase_Core_DateAndTime_Eventing_TimeMeasurerUpdatedEventArgs">DevCase.Core.DateAndTime.Eventing.TimeMeasurerUpdatedEventArgs</a><br /></dd></dl>

## See Also


#### Reference
<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime Namespace</a><br />