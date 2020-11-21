# TenMinuteMail Constructor (TimeSpan)
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TenMinuteMail(
	TimeSpan updateInterval
)
```

**VB**<br />
``` VB
Public Sub New ( 
	updateInterval As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim updateInterval As TimeSpan

Dim instance As New TenMinuteMail(updateInterval)
```

**C++**<br />
``` C++
public:
TenMinuteMail(
	TimeSpan updateInterval
)
```

**F#**<br />
``` F#
new : 
        updateInterval : TimeSpan -> TenMinuteMail
```


#### Parameters
&nbsp;<dl><dt>updateInterval</dt><dd>Type: System.TimeSpan<br />The time interval to check for new incoming messages. 

 Be aware that 10minutemail.com server's update interval are 10 seconds by default.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Update interval must be in range between 10 to 60 seconds. - updateInterval</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="Overload_DevCase_Core_NET_TenMinuteMail__ctor">TenMinuteMail Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />