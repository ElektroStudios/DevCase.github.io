# Client.DeleteDirectory Method 
 

Creates a directory on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void DeleteDirectory(
	string directorypath,
	bool force,
	FtpListOption ftpListOption = FtpListOption.AllFiles|FtpListOption.ForceList
)
```

**VB**<br />
``` VB
Public Sub DeleteDirectory ( 
	directorypath As String,
	force As Boolean,
	Optional ftpListOption As FtpListOption = FtpListOption.AllFiles Or FtpListOption.ForceList
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim directorypath As String
Dim force As Boolean
Dim ftpListOption As FtpListOption

instance.DeleteDirectory(directorypath, 
	force, ftpListOption)
```

**C++**<br />
``` C++
public:
void DeleteDirectory(
	String^ directorypath, 
	bool force, 
	FtpListOption ftpListOption = FtpListOption::AllFiles|FtpListOption::ForceList
)
```

**F#**<br />
``` F#
member DeleteDirectory : 
        directorypath : string * 
        force : bool * 
        ?ftpListOption : FtpListOption 
(* Defaults:
        let _ftpListOption = defaultArg ftpListOption FtpListOption.AllFiles|FtpListOption.ForceList
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>directorypath</dt><dd>Type: System.String<br />The ftp directory path.</dd><dt>force</dt><dd>Type: System.Boolean<br />Try to force all non-existant pieces of the path to be created.</dd><dt>ftpListOption (Optional)</dt><dd>Type: FtpListOption<br />\[Missing <param name="ftpListOption"/> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.DeleteDirectory(System.String,System.Boolean,FluentFTP.FtpListOption)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />