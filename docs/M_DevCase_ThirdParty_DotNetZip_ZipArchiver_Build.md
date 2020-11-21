# ZipArchiver.Build Method (IEnumerable(String), String)
 

Compresses the specified source files or diretories into a Zip archive using the default compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Build(
	IEnumerable<string> sourceFileOrDirs,
	string outputFilepath
)
```

**VB**<br />
``` VB
Public Function Build ( 
	sourceFileOrDirs As IEnumerable(Of String),
	outputFilepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim sourceFileOrDirs As IEnumerable(Of String)
Dim outputFilepath As String
Dim returnValue As String

returnValue = instance.Build(sourceFileOrDirs, 
	outputFilepath)
```

**C++**<br />
``` C++
public:
String^ Build(
	IEnumerable<String^>^ sourceFileOrDirs, 
	String^ outputFilepath
)
```

**F#**<br />
``` F#
member Build : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDirs</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source files or diretories.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting Zip archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build">Build Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />