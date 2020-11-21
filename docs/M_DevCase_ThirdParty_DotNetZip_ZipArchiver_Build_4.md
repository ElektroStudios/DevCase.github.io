# ZipArchiver.Build Method (String, String)
 

Compresses the specified source file or diretory into a Zip archive using the default compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Build(
	string sourceFileOrDir,
	string outputFilepath
)
```

**VB**<br />
``` VB
Public Function Build ( 
	sourceFileOrDir As String,
	outputFilepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim sourceFileOrDir As String
Dim outputFilepath As String
Dim returnValue As String

returnValue = instance.Build(sourceFileOrDir, 
	outputFilepath)
```

**C++**<br />
``` C++
public:
String^ Build(
	String^ sourceFileOrDir, 
	String^ outputFilepath
)
```

**F#**<br />
``` F#
member Build : 
        sourceFileOrDir : string * 
        outputFilepath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDir</dt><dd>Type: System.String<br />The source file or diretory.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting Zip archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build">Build Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />