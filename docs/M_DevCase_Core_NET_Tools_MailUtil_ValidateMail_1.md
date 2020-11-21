# MailUtil.ValidateMail Method (String)
 

Validates a mail address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ValidateMail(
	string address
)
```

**VB**<br />
``` VB
Public Shared Function ValidateMail ( 
	address As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim returnValue As Boolean

returnValue = MailUtil.ValidateMail(address)
```

**C++**<br />
``` C++
public:
static bool ValidateMail(
	String^ address
)
```

**F#**<br />
``` F#
static member ValidateMail : 
        address : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The mail address.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the mail address is valid, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isValid As Boolean = ValidateMail("Address@Gmail.com")
Dim isValid As Boolean = ValidateMail("mailto:Address@Gmail.com")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_ValidateMail">ValidateMail Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />