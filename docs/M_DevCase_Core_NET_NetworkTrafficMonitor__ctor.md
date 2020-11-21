# NetworkTrafficMonitor Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public NetworkTrafficMonitor(
	string interfaceName
)
```

**VB**<br />
``` VB
Public Sub New ( 
	interfaceName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim interfaceName As String

Dim instance As New NetworkTrafficMonitor(interfaceName)
```

**C++**<br />
``` C++
public:
NetworkTrafficMonitor(
	String^ interfaceName
)
```

**F#**<br />
``` F#
new : 
        interfaceName : string -> NetworkTrafficMonitor
```


#### Parameters
&nbsp;<dl><dt>interfaceName</dt><dd>Type: System.String<br />The name of the interface to monitor.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotImplementedException</td><td>Performance Counters doesn't include the category.</td></tr><tr><td>ArgumentException</td><td>The specified interface is not available or doesn't exist.;interfaceName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />