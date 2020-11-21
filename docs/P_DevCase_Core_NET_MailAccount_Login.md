# MailAccount.Login Property 
 

Gets or sets the username and password.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public NetworkCredential Login { get; set; }
```

**VB**<br />
``` VB
Public Property Login As NetworkCredential
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MailAccount
Dim value As NetworkCredential

value = instance.Login

instance.Login = value
```

**C++**<br />
``` C++
public:
property NetworkCredential^ Login {
	NetworkCredential^ get ();
	void set (NetworkCredential^ value);
}
```

**F#**<br />
``` F#
member Login : NetworkCredential with get, set

```


#### Property Value
Type: NetworkCredential<br />The username and password.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_MailAccount">MailAccount Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />