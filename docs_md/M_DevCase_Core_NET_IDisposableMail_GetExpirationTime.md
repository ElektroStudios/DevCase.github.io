# IDisposableMail.GetExpirationTime Method 
 

Gets the time left to expire the current temporary mail address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
TimeSpan GetExpirationTime()
```

**VB**<br />
``` VB
Function GetExpirationTime As TimeSpan
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDisposableMail
Dim returnValue As TimeSpan

returnValue = instance.GetExpirationTime()
```

**C++**<br />
``` C++
TimeSpan GetExpirationTime()
```

**F#**<br />
``` F#
abstract GetExpirationTime : unit -> TimeSpan 

```


#### Return Value
Type: TimeSpan<br />The time left to expire the current temporary mail address.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_IDisposableMail">IDisposableMail Interface</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />