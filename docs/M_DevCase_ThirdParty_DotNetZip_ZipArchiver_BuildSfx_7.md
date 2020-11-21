# ZipArchiver.BuildSfx Method (String, String, CompressionMethod, CompressionLevel)
 

Compresses the specified source file or diretory into a self-extracting archive (SFX) using the specified compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string BuildSfx(
	string sourceFileOrDir,
	string outputFilepath,
	CompressionMethod compressionMethod,
	CompressionLevel compressionLevel
)
```

**VB**<br />
``` VB
Public Function BuildSfx ( 
	sourceFileOrDir As String,
	outputFilepath As String,
	compressionMethod As CompressionMethod,
	compressionLevel As CompressionLevel
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim sourceFileOrDir As String
Dim outputFilepath As String
Dim compressionMethod As CompressionMethod
Dim compressionLevel As CompressionLevel
Dim returnValue As String

returnValue = instance.BuildSfx(sourceFileOrDir, 
	outputFilepath, compressionMethod, 
	compressionLevel)
```

**C++**<br />
``` C++
public:
String^ BuildSfx(
	String^ sourceFileOrDir, 
	String^ outputFilepath, 
	CompressionMethod compressionMethod, 
	CompressionLevel compressionLevel
)
```

**F#**<br />
``` F#
member BuildSfx : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDir</dt><dd>Type: System.String<br />The source file or diretory.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output SFX file to create.</dd><dt>compressionMethod</dt><dd>Type: CompressionMethod<br />The compression method.</dd><dt>compressionLevel</dt><dd>Type: CompressionLevel<br />The compression level.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting SFX file.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx">BuildSfx Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />