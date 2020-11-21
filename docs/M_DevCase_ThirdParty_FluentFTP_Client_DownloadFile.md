# Client.DownloadFile Method 
 

Downloads a file from the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void DownloadFile(
	ref WebClient refClient,
	string filepath,
	string localfilepath,
	bool asynchronous = false
)
```

**VB**<br />
``` VB
Public Sub DownloadFile ( 
	ByRef refClient As WebClient,
	filepath As String,
	localfilepath As String,
	Optional asynchronous As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim refClient As WebClient
Dim filepath As String
Dim localfilepath As String
Dim asynchronous As Boolean

instance.DownloadFile(refClient, filepath, 
	localfilepath, asynchronous)
```

**C++**<br />
``` C++
public:
void DownloadFile(
	WebClient^% refClient, 
	String^ filepath, 
	String^ localfilepath, 
	bool asynchronous = false
)
```

**F#**<br />
``` F#
member DownloadFile : 
        refClient : WebClient byref * 
        filepath : string * 
        localfilepath : string * 
        ?asynchronous : bool 
(* Defaults:
        let _asynchronous = defaultArg asynchronous false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>refClient</dt><dd>Type: System.Net.WebClient<br />The WebClient object to download the file.</dd><dt>filepath</dt><dd>Type: System.String<br />The ftp fle path.</dd><dt>localfilepath</dt><dd>Type: System.String<br />Specifies the local path where to save the downloaded file.</dd><dt>asynchronous (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="asynchronous"/> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.DownloadFile(System.Net.WebClient@,System.String,System.String,System.Boolean)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />