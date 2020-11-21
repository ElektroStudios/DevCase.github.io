# Client.UploadFile Method 
 

Uploads a file to the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void UploadFile(
	ref WebClient refClient,
	string localfilepath,
	string filepath = null,
	bool asynchronous = false
)
```

**VB**<br />
``` VB
Public Sub UploadFile ( 
	ByRef refClient As WebClient,
	localfilepath As String,
	Optional filepath As String = Nothing,
	Optional asynchronous As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim refClient As WebClient
Dim localfilepath As String
Dim filepath As String
Dim asynchronous As Boolean

instance.UploadFile(refClient, localfilepath, 
	filepath, asynchronous)
```

**C++**<br />
``` C++
public:
void UploadFile(
	WebClient^% refClient, 
	String^ localfilepath, 
	String^ filepath = nullptr, 
	bool asynchronous = false
)
```

**F#**<br />
``` F#
member UploadFile : 
        refClient : WebClient byref * 
        localfilepath : string * 
        ?filepath : string * 
        ?asynchronous : bool 
(* Defaults:
        let _filepath = defaultArg filepath null
        let _asynchronous = defaultArg asynchronous false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>refClient</dt><dd>Type: System.Net.WebClient<br />The WebClient object to upload the file.</dd><dt>localfilepath</dt><dd>Type: System.String<br />Specifies the local path where to save the downloaded file.</dd><dt>filepath (Optional)</dt><dd>Type: System.String<br />The ftp fle path.</dd><dt>asynchronous (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="asynchronous"/> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.UploadFile(System.Net.WebClient@,System.String,System.String,System.Boolean)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />