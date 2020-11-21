# ZipArchiver.Extract Method (String, String, ExtractExistingFileAction, String)
 

Extracts the encrypted contents of the source zip archive to the specified diretory.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Extract(
	string sourceFilePath,
	string outputDirectoryPath,
	ExtractExistingFileAction overwrite,
	string password
)
```

**VB**<br />
``` VB
Public Function Extract ( 
	sourceFilePath As String,
	outputDirectoryPath As String,
	overwrite As ExtractExistingFileAction,
	password As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim sourceFilePath As String
Dim outputDirectoryPath As String
Dim overwrite As ExtractExistingFileAction
Dim password As String
Dim returnValue As String

returnValue = instance.Extract(sourceFilePath, 
	outputDirectoryPath, overwrite, 
	password)
```

**C++**<br />
``` C++
public:
String^ Extract(
	String^ sourceFilePath, 
	String^ outputDirectoryPath, 
	ExtractExistingFileAction overwrite, 
	String^ password
)
```

**F#**<br />
``` F#
member Extract : 
        sourceFilePath : string * 
        outputDirectoryPath : string * 
        overwrite : ExtractExistingFileAction * 
        password : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFilePath</dt><dd>Type: System.String<br />The source zip file.</dd><dt>outputDirectoryPath</dt><dd>Type: System.String<br />The output directory path.</dd><dt>overwrite</dt><dd>Type: ExtractExistingFileAction<br />A value that indicates whether to overwrite any existing file during the extraction.</dd><dt>password</dt><dd>Type: System.String<br />The zip password.</dd></dl>

#### Return Value
Type: String<br />The full path of the output directory.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetZip_ZipArchiver_Extract">Extract Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />