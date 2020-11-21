# EASendMailUtil.HotmailSender Method 
 

Sends an E-Mail through Hotmail.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_EASendMail">DevCase.ThirdParty.EASendMail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void HotmailSender(
	string username,
	string password,
	string fromAddress,
	string toAddress,
	string subject,
	string body,
	string[] attachments = null
)
```

**VB**<br />
``` VB
Public Shared Sub HotmailSender ( 
	username As String,
	password As String,
	fromAddress As String,
	toAddress As String,
	subject As String,
	body As String,
	Optional attachments As String() = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim password As String
Dim fromAddress As String
Dim toAddress As String
Dim subject As String
Dim body As String
Dim attachments As String()

EASendMailUtil.HotmailSender(username, password, 
	fromAddress, toAddress, subject, 
	body, attachments)
```

**C++**<br />
``` C++
public:
static void HotmailSender(
	String^ username, 
	String^ password, 
	String^ fromAddress, 
	String^ toAddress, 
	String^ subject, 
	String^ body, 
	array<String^>^ attachments = nullptr
)
```

**F#**<br />
``` F#
static member HotmailSender : 
        username : string * 
        password : string * 
        fromAddress : string * 
        toAddress : string * 
        subject : string * 
        body : string * 
        ?attachments : string[] 
(* Defaults:
        let _attachments = defaultArg attachments null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The Hotmail account username.</dd><dt>password</dt><dd>Type: System.String<br />The Hotmail account password.</dd><dt>fromAddress</dt><dd>Type: System.String<br />The sourceHotmail address.</dd><dt>toAddress</dt><dd>Type: System.String<br />The destiny address.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>attachments (Optional)</dt><dd>Type: System.String[]<br />The mail attachments.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
HotmailSender(username:="username",
              password:="pass",
              fromAddress:="name@hotmail.com",
              toAddress:="someone@gmail.com",
              subject:="Mail subject",
              body:="Mail body",
              attachments:={"C:\File1.ext", "C:\file2.ext"})
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_EASendMail_EASendMailUtil">EASendMailUtil Class</a><br /><a href="N_DevCase_ThirdParty_EASendMail">DevCase.ThirdParty.EASendMail Namespace</a><br />