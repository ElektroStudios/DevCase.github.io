# MailUtil.MailTo Method (MailMessage)
 

Runs the default mail client to send an email with the specified parameters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MailTo(
	MailMessage msg
)
```

**VB**<br />
``` VB
Public Shared Sub MailTo ( 
	msg As MailMessage
)
```

**VB Usage**<br />
``` VB Usage
Dim msg As MailMessageMailUtil.MailTo(msg)
```

**C++**<br />
``` C++
public:
static void MailTo(
	MailMessage^ msg
)
```

**F#**<br />
``` F#
static member MailTo : 
        msg : MailMessage -> unit 

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: System.Net.Mail.MailMessage<br />A MailMessage that contains the mail address, subject and body to send.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim msg As New MailMessage()
msg.To.Add("ElektroStudios@Support.com")
msg.Subject = String.Format("Exception thrown by {0}.exe", Process.GetCurrentProcess.ProcessName)
msg.Body = "A gift for you!"

MailTo(msg)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_MailTo">MailTo Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />