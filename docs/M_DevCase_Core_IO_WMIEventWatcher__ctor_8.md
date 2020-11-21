# WMIEventWatcher Constructor (String, String, String[], UInt32)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_WMIEventWatcher">WMIEventWatcher</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WMIEventWatcher(
	string eventClassName,
	string condition,
	string[] groupByPropertyList,
	uint groupWithinInterval
)
```

**VB**<br />
``` VB
Public Sub New ( 
	eventClassName As String,
	condition As String,
	groupByPropertyList As String(),
	groupWithinInterval As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim eventClassName As String
Dim condition As String
Dim groupByPropertyList As String()
Dim groupWithinInterval As UInteger

Dim instance As New WMIEventWatcher(eventClassName, 
	condition, groupByPropertyList, 
	groupWithinInterval)
```

**C++**<br />
``` C++
public:
WMIEventWatcher(
	String^ eventClassName, 
	String^ condition, 
	array<String^>^ groupByPropertyList, 
	unsigned int groupWithinInterval
)
```

**F#**<br />
``` F#
new : 
        eventClassName : string * 
        condition : string * 
        groupByPropertyList : string[] * 
        groupWithinInterval : uint32 -> WMIEventWatcher
```


#### Parameters
&nbsp;<dl><dt>eventClassName</dt><dd>Type: System.String<br />The name of the WMI event class to subscribe for.</dd><dt>condition</dt><dd>Type: System.String<br />The condition to be applied to events of the specified class in the *eventClassName* parameter.</dd><dt>groupByPropertyList</dt><dd>Type: System.String[]<br />The properties in the event class by which the events should be grouped.</dd><dt>groupWithinInterval</dt><dd>Type: System.UInt32<br />The interval, in seconds, of the specified interval at which WMI sends one aggregate event, rather than many events.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_WMIEventWatcher">WMIEventWatcher Class</a><br /><a href="Overload_DevCase_Core_IO_WMIEventWatcher__ctor">WMIEventWatcher Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />