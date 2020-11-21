# Client.GetFiles Method 
 

Gets a file list on the specified path.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FtpListItem[] GetFiles(
	string directorypath,
	FtpListOption ftpListOption = FtpListOption.AllFiles
)
```

**VB**<br />
``` VB
Public Function GetFiles ( 
	directorypath As String,
	Optional ftpListOption As FtpListOption = FtpListOption.AllFiles
) As FtpListItem()
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim directorypath As String
Dim ftpListOption As FtpListOption
Dim returnValue As FtpListItem()

returnValue = instance.GetFiles(directorypath, 
	ftpListOption)
```

**C++**<br />
``` C++
public:
array<FtpListItem^>^ GetFiles(
	String^ directorypath, 
	FtpListOption ftpListOption = FtpListOption::AllFiles
)
```

**F#**<br />
``` F#
member GetFiles : 
        directorypath : string * 
        ?ftpListOption : FtpListOption 
(* Defaults:
        let _ftpListOption = defaultArg ftpListOption FtpListOption.AllFiles
*)
-> FtpListItem[] 

```


#### Parameters
&nbsp;<dl><dt>directorypath</dt><dd>Type: System.String<br />The ftp directory path.</dd><dt>ftpListOption (Optional)</dt><dd>Type: FtpListOption<br />\[Missing <param name="ftpListOption"/> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.GetFiles(System.String,FluentFTP.FtpListOption)"\]</dd></dl>

#### Return Value
Type: FtpListItem[]<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.GetFiles(System.String,FluentFTP.FtpListOption)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />