# SevenZipArchiver.Build Method (String, String, CompressionMethod, CompressionLevel, Int32)
 

Builds a compressed multi-volume archive containing the source file or directory using the default compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Build(
	string sourceFileOrDir,
	string outputFilepath,
	CompressionMethod compressionMethod,
	CompressionLevel compressionLevel,
	int volumeSize
)
```

**VB**<br />
``` VB
Public Function Build ( 
	sourceFileOrDir As String,
	outputFilepath As String,
	compressionMethod As CompressionMethod,
	compressionLevel As CompressionLevel,
	volumeSize As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As SevenZipArchiver
Dim sourceFileOrDir As String
Dim outputFilepath As String
Dim compressionMethod As CompressionMethod
Dim compressionLevel As CompressionLevel
Dim volumeSize As Integer
Dim returnValue As String

returnValue = instance.Build(sourceFileOrDir, 
	outputFilepath, compressionMethod, 
	compressionLevel, volumeSize)
```

**C++**<br />
``` C++
public:
String^ Build(
	String^ sourceFileOrDir, 
	String^ outputFilepath, 
	CompressionMethod compressionMethod, 
	CompressionLevel compressionLevel, 
	int volumeSize
)
```

**F#**<br />
``` F#
member Build : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel * 
        volumeSize : int -> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDir</dt><dd>Type: System.String<br />The source file or diretory to compress.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd><dt>compressionMethod</dt><dd>Type: CompressionMethod<br />The compression method.</dd><dt>compressionLevel</dt><dd>Type: CompressionLevel<br />The compression level.</dd><dt>volumeSize</dt><dd>Type: System.Int32<br />The volumes size, in bytes.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting compressed archive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver">SevenZipArchiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver_Build">Build Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />