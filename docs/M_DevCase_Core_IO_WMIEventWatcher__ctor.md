# WMIEventWatcher Constructor (SelectQuery)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_WMIEventWatcher">WMIEventWatcher</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WMIEventWatcher(
	SelectQuery query
)
```

**VB**<br />
``` VB
Public Sub New ( 
	query As SelectQuery
)
```

**VB Usage**<br />
``` VB Usage
Dim query As SelectQuery

Dim instance As New WMIEventWatcher(query)
```

**C++**<br />
``` C++
public:
WMIEventWatcher(
	SelectQuery^ query
)
```

**F#**<br />
``` F#
new : 
        query : SelectQuery -> WMIEventWatcher
```


#### Parameters
&nbsp;<dl><dt>query</dt><dd>Type: System.Management.SelectQuery<br />The WMI select query of the event class to subscribe for.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_WMIEventWatcher">WMIEventWatcher Class</a><br /><a href="Overload_DevCase_Core_IO_WMIEventWatcher__ctor">WMIEventWatcher Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />