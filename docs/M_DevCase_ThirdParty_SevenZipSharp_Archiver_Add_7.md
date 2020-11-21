# Archiver.Add Method (String, String, String, CompressionMethod, CompressionLevel)
 

Appends the source file or directory into the specified compressed archive, with a password, using the specified compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string Add(
	string sourceFileOrDir,
	string outputFilepath,
	string password,
	CompressionMethod compressionMethod,
	CompressionLevel compressionLevel
)
```

**VB**<br />
``` VB
Public Overridable Function Add ( 
	sourceFileOrDir As String,
	outputFilepath As String,
	password As String,
	compressionMethod As CompressionMethod,
	compressionLevel As CompressionLevel
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim sourceFileOrDir As String
Dim outputFilepath As String
Dim password As String
Dim compressionMethod As CompressionMethod
Dim compressionLevel As CompressionLevel
Dim returnValue As String

returnValue = instance.Add(sourceFileOrDir, 
	outputFilepath, password, compressionMethod, 
	compressionLevel)
```

**C++**<br />
``` C++
public:
virtual String^ Add(
	String^ sourceFileOrDir, 
	String^ outputFilepath, 
	String^ password, 
	CompressionMethod compressionMethod, 
	CompressionLevel compressionLevel
)
```

**F#**<br />
``` F#
abstract Add : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        password : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 
override Add : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        password : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 
```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDir</dt><dd>Type: System.String<br />The source file or diretory to append.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd><dt>password</dt><dd>Type: System.String<br />The password.</dd><dt>compressionMethod</dt><dd>Type: CompressionMethod<br />The compression method.</dd><dt>compressionLevel</dt><dd>Type: CompressionLevel<br />The compression level.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting compressed archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver_Add">Add Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />