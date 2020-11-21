# FtpUtil.Upload Method 
 

Uploads a file to an FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Upload(
	string filePath,
	string ftpPath,
	string user = "",
	string pass = ""
)
```

**VB**<br />
``` VB
Public Shared Sub Upload ( 
	filePath As String,
	ftpPath As String,
	Optional user As String = "",
	Optional pass As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim ftpPath As String
Dim user As String
Dim pass As StringFtpUtil.Upload(filePath, ftpPath, user, 
	pass)
```

**C++**<br />
``` C++
public:
static void Upload(
	String^ filePath, 
	String^ ftpPath, 
	String^ user = L"", 
	String^ pass = L""
)
```

**F#**<br />
``` F#
static member Upload : 
        filePath : string * 
        ftpPath : string * 
        ?user : string * 
        ?pass : string 
(* Defaults:
        let _user = defaultArg user ""
        let _pass = defaultArg pass ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The source filepath.</dd><dt>ftpPath</dt><dd>Type: System.String<br />The directory path of the FTP server.</dd><dt>user (Optional)</dt><dd>Type: System.String<br />The username, if any. 

 This value can be an empty string.</dd><dt>pass (Optional)</dt><dd>Type: System.String<br />The password. 

 This value can be an empty string.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Upload("C:\File.txt", "ftp://127.0.0.1/Folder/", "User", "Pass")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_FtpUtil">FtpUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />