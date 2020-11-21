# TenMinuteMail.IsBlocked Property 
 

Gets a value indicating whether the temporary mail service is blocked. 

 If `true` (`True` in Visual Basic), this means you have requested too many temporary mail addresses from your IP address too quickly. 

 And you must wait some minutes to be able use 10minutemail.com service again.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsBlocked { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property IsBlocked As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim value As Boolean

value = instance.IsBlocked

```

**C++**<br />
``` C++
public:
property bool IsBlocked {
	bool get ();
}
```

**F#**<br />
``` F#
member IsBlocked : bool with get

```


#### Property Value
Type: Boolean<br />If `true` (`True` in Visual Basic), this means you have requested too many temporary mail addresses from your IP address too quickly. 

 And you must wait some minutes to be able use 10minutemail.com service again.; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />