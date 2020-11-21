# IDisposableMail.CreateNew Method 
 

Creates a new temporary mail address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void CreateNew(
	TimeSpan updateInterval
)
```

**VB**<br />
``` VB
Sub CreateNew ( 
	updateInterval As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDisposableMail
Dim updateInterval As TimeSpan

instance.CreateNew(updateInterval)
```

**C++**<br />
``` C++
void CreateNew(
	TimeSpan updateInterval
)
```

**F#**<br />
``` F#
abstract CreateNew : 
        updateInterval : TimeSpan -> unit 

```


#### Parameters
&nbsp;<dl><dt>updateInterval</dt><dd>Type: System.TimeSpan<br />The time interval to check for new incoming mail messages.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_IDisposableMail">IDisposableMail Interface</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />