# DevWebClient.RequestTimeout Property 
 

Gets or sets the time interval, in milliseconds, until the requests made by this <a href="T_DevCase_Core_NET_DevWebClient">DevWebClient</a> times out.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int RequestTimeout { get; set; }
```

**VB**<br />
``` VB
Public Property RequestTimeout As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebClient
Dim value As Integer

value = instance.RequestTimeout

instance.RequestTimeout = value
```

**C++**<br />
``` C++
public:
property int RequestTimeout {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member RequestTimeout : int with get, set

```


#### Property Value
Type: Int32<br />The time interval, in milliseconds, until the requests made by this <a href="T_DevCase_Core_NET_DevWebClient">DevWebClient</a> times out, or Infinite to indicate that the request does not time out.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_DevWebClient">DevWebClient Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />