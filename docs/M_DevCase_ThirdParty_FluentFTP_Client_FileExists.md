# Client.FileExists Method 
 

Checks if a file exist on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool FileExists(
	string filepath,
	FtpListOption ftpListOption = FtpListOption.AllFiles|FtpListOption.ForceList
)
```

**VB**<br />
``` VB
Public Function FileExists ( 
	filepath As String,
	Optional ftpListOption As FtpListOption = FtpListOption.AllFiles Or FtpListOption.ForceList
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim filepath As String
Dim ftpListOption As FtpListOption
Dim returnValue As Boolean

returnValue = instance.FileExists(filepath, 
	ftpListOption)
```

**C++**<br />
``` C++
public:
bool FileExists(
	String^ filepath, 
	FtpListOption ftpListOption = FtpListOption::AllFiles|FtpListOption::ForceList
)
```

**F#**<br />
``` F#
member FileExists : 
        filepath : string * 
        ?ftpListOption : FtpListOption 
(* Defaults:
        let _ftpListOption = defaultArg ftpListOption FtpListOption.AllFiles|FtpListOption.ForceList
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath on the FTP.</dd><dt>ftpListOption (Optional)</dt><dd>Type: FtpListOption<br />\[Missing <param name="ftpListOption"/> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.FileExists(System.String,FluentFTP.FtpListOption)"\]</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.FileExists(System.String,FluentFTP.FtpListOption)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />