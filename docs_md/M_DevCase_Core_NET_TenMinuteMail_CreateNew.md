# TenMinuteMail.CreateNew Method 
 

Creates a new temporary mail address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void CreateNew(
	TimeSpan updateInterval
)
```

**VB**<br />
``` VB
Public Overridable Sub CreateNew ( 
	updateInterval As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim updateInterval As TimeSpan

instance.CreateNew(updateInterval)
```

**C++**<br />
``` C++
public:
virtual void CreateNew(
	TimeSpan updateInterval
)
```

**F#**<br />
``` F#
abstract CreateNew : 
        updateInterval : TimeSpan -> unit 
override CreateNew : 
        updateInterval : TimeSpan -> unit 
```


#### Parameters
&nbsp;<dl><dt>updateInterval</dt><dd>Type: System.TimeSpan<br />The time interval to check for new incoming messages. 

 Be aware that 10minutemail.com server's update interval are 10 seconds by default.</dd></dl>

#### Implements
<a href="M_DevCase_Core_NET_IDisposableMail_CreateNew">IDisposableMail.CreateNew(TimeSpan)</a><br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Update interval must be in range between 10 to 60 seconds. - updateInterval</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />