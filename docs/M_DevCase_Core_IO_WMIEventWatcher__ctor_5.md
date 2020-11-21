# WMIEventWatcher Constructor (String, Single)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_WMIEventWatcher">WMIEventWatcher</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WMIEventWatcher(
	string eventClassName,
	float withinInterval
)
```

**VB**<br />
``` VB
Public Sub New ( 
	eventClassName As String,
	withinInterval As Single
)
```

**VB Usage**<br />
``` VB Usage
Dim eventClassName As String
Dim withinInterval As Single

Dim instance As New WMIEventWatcher(eventClassName, 
	withinInterval)
```

**C++**<br />
``` C++
public:
WMIEventWatcher(
	String^ eventClassName, 
	float withinInterval
)
```

**F#**<br />
``` F#
new : 
        eventClassName : string * 
        withinInterval : float32 -> WMIEventWatcher
```


#### Parameters
&nbsp;<dl><dt>eventClassName</dt><dd>Type: System.String<br />The name of the WMI event class to subscribe for.</dd><dt>withinInterval</dt><dd>Type: System.Single<br />The interval, in seconds, that WMI will check for changes that occur to instances of the events of the specified class in the *eventClassName* parameter.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_WMIEventWatcher">WMIEventWatcher Class</a><br /><a href="Overload_DevCase_Core_IO_WMIEventWatcher__ctor">WMIEventWatcher Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />