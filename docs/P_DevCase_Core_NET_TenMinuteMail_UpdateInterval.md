# TenMinuteMail.UpdateInterval Property 
 

Gets the time interval to check for new incoming messages.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TimeSpan UpdateInterval { get; set; }
```

**VB**<br />
``` VB
Public Property UpdateInterval As TimeSpan
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim value As TimeSpan

value = instance.UpdateInterval

instance.UpdateInterval = value
```

**C++**<br />
``` C++
public:
property TimeSpan UpdateInterval {
	TimeSpan get ();
	void set (TimeSpan value);
}
```

**F#**<br />
``` F#
member UpdateInterval : TimeSpan with get, set

```


#### Property Value
Type: TimeSpan<br />The time interval to check for new incoming messages.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />