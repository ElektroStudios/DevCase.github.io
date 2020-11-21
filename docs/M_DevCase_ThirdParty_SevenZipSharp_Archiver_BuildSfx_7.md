# Archiver.BuildSfx Method (String, String, String, SevenZipSharpSfxModule, CompressionMethod, CompressionLevel)
 

Builds a self-extracting archive (SFX), with a password, containing the source file or directory using the specified compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string BuildSfx(
	string sourceFileOrDir,
	string outputFilepath,
	string password,
	SevenZipSharpSfxModule sfxModule,
	CompressionMethod compressionMethod,
	CompressionLevel compressionLevel
)
```

**VB**<br />
``` VB
Public Overridable Function BuildSfx ( 
	sourceFileOrDir As String,
	outputFilepath As String,
	password As String,
	sfxModule As SevenZipSharpSfxModule,
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
Dim sfxModule As SevenZipSharpSfxModule
Dim compressionMethod As CompressionMethod
Dim compressionLevel As CompressionLevel
Dim returnValue As String

returnValue = instance.BuildSfx(sourceFileOrDir, 
	outputFilepath, password, sfxModule, 
	compressionMethod, compressionLevel)
```

**C++**<br />
``` C++
public:
virtual String^ BuildSfx(
	String^ sourceFileOrDir, 
	String^ outputFilepath, 
	String^ password, 
	SevenZipSharpSfxModule sfxModule, 
	CompressionMethod compressionMethod, 
	CompressionLevel compressionLevel
)
```

**F#**<br />
``` F#
abstract BuildSfx : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        password : string * 
        sfxModule : SevenZipSharpSfxModule * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 
override BuildSfx : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        password : string * 
        sfxModule : SevenZipSharpSfxModule * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel -> string 
```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDir</dt><dd>Type: System.String<br />The source file or diretory to compress.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd><dt>password</dt><dd>Type: System.String<br />The password.</dd><dt>sfxModule</dt><dd>Type: <a href="T_DevCase_ThirdParty_SevenZipSharp_SevenZipSharpSfxModule">DevCase.ThirdParty.SevenZipSharp.SevenZipSharpSfxModule</a><br />The SFX module type.</dd><dt>compressionMethod</dt><dd>Type: CompressionMethod<br />The compression method.</dd><dt>compressionLevel</dt><dd>Type: CompressionLevel<br />The compression level.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting self-extracting archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx">BuildSfx Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />