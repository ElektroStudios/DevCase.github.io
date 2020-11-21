# MailUtil.MailTo Method (String, String, String)
 

Runs the default mail client to send an email with the specified parameters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MailTo(
	string address,
	string subject,
	string body
)
```

**VB**<br />
``` VB
Public Shared Sub MailTo ( 
	address As String,
	subject As String,
	body As String
)
```

**VB Usage**<br />
``` VB Usage
Dim address As String
Dim subject As String
Dim body As StringMailUtil.MailTo(address, subject, body)
```

**C++**<br />
``` C++
public:
static void MailTo(
	String^ address, 
	String^ subject, 
	String^ body
)
```

**F#**<br />
``` F#
static member MailTo : 
        address : string * 
        subject : string * 
        body : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.String<br />The mail address, or multiple adresses separated by a ";" character.</dd><dt>subject</dt><dd>Type: System.String<br />The subject of the email.</dd><dt>body</dt><dd>Type: System.String<br />The body content of the email.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
MailTo(mailAddress:="Name@Server.com",
       subject:="A gift for you!",
       body:="Hello World!")

MailTo(mailAddress:="Name1@Server1.com;Name2@Server2.com",
       subject:="A gift for you!",
       body:="Hello World!")

MailTo(mailAddress:="ElektroStudios@Support.com",
       subject:=String.Format("Exception thrown by {0}.exe", Process.GetCurrentProcess.ProcessName),
       body:="A gift for you!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_MailTo">MailTo Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />