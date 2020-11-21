# Archiver.BuildSfx Method (IEnumerable(String), String, SevenZipSharpSfxModule)
 

Builds a self-extracting archive (SFX) containing the source file or directory using the default compression parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string BuildSfx(
	IEnumerable<string> sourceFileOrDirs,
	string outputFilepath,
	SevenZipSharpSfxModule sfxModule
)
```

**VB**<br />
``` VB
Public Overridable Function BuildSfx ( 
	sourceFileOrDirs As IEnumerable(Of String),
	outputFilepath As String,
	sfxModule As SevenZipSharpSfxModule
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim sourceFileOrDirs As IEnumerable(Of String)
Dim outputFilepath As String
Dim sfxModule As SevenZipSharpSfxModule
Dim returnValue As String

returnValue = instance.BuildSfx(sourceFileOrDirs, 
	outputFilepath, sfxModule)
```

**C++**<br />
``` C++
public:
virtual String^ BuildSfx(
	IEnumerable<String^>^ sourceFileOrDirs, 
	String^ outputFilepath, 
	SevenZipSharpSfxModule sfxModule
)
```

**F#**<br />
``` F#
abstract BuildSfx : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string * 
        sfxModule : SevenZipSharpSfxModule -> string 
override BuildSfx : 
        sourceFileOrDirs : IEnumerable<string> * 
        outputFilepath : string * 
        sfxModule : SevenZipSharpSfxModule -> string 
```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDirs</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source files or diretories to compress.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output file to create.</dd><dt>sfxModule</dt><dd>Type: <a href="T_DevCase_ThirdParty_SevenZipSharp_SevenZipSharpSfxModule">DevCase.ThirdParty.SevenZipSharp.SevenZipSharpSfxModule</a><br />The SFX module type.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting self-extracting archive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="Overload_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx">BuildSfx Overload</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />