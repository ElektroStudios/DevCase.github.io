# Archiver.Build Method (IEnumerable(String), String, CompressionMethod, CompressionLevel)
 

Builds a compressed archive containing the source file or directory using the specified compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string Build(
	IEnumerable<string> sourceFileOrDirs,
	string outputFilepath,
	CompressionMethod compressionMethod,
	CompressionLevel compressionLevel
)
```

**VB**<br />
``` VB
Public Overridable Function Build ( 
	sourceFileOrDirs As IEnumerable(Of String),
	outputFilepath As String,
	compressionMethod As CompressionMethod,
	compressionLevel As CompressionLevel
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim sourceFileOrDirs As IEnumerable(Of String)
Dim outputFilepath As String
Dim compressionMethod As CompressionMethod
Dim compressionLevel As CompressionLevel
Dim returnValue As String

returnValue = instance.Build(sourceFileOrDirs, 
	outputFilepath, compressionMethod, 
	compressionLevel)
```

**C++**<br />
``` C++
public:
virtual String^ Build(
	IEnumerable<String^>^ sourceFileOrDirs, 
	String^ outputFilepath, 
	CompressionMethod compressionMethod, 
	CompressionLevel compressionLevel
)
```

**F#**<br />
``` F#
abstract Build : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 
override Build : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 
```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDirs</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source files or diretories to compress.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd><dt>compressionMethod</dt><dd>Type: CompressionMethod<br />The compression method.</dd><dt>compressionLevel</dt><dd>Type: CompressionLevel<br />The compression level.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting compressed archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver_Build">Build Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />