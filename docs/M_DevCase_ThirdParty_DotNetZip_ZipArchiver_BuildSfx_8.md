# ZipArchiver.BuildSfx Method (String, String, CompressionMethod, CompressionLevel, String, Boolean, ExtractExistingFileAction, Boolean, String, String, SelfExtractorFlavor, String)
 

Compresses the specified source file or diretory into a self-extracting archive (SFX), using the specified compression and SFX parameters.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string BuildSfx(
	string sourceFileOrDir,
	string outputFilepath,
	CompressionMethod compressionMethod,
	CompressionLevel compressionLevel,
	string extractionDirectory,
	bool silentExtraction,
	ExtractExistingFileAction overwriteFiles,
	bool deleteExtractedFilesAfterExtraction,
	string icon,
	string windowTitle,
	SelfExtractorFlavor windowStyle,
	string commandLineArgument
)
```

**VB**<br />
``` VB
Public Function BuildSfx ( 
	sourceFileOrDir As String,
	outputFilepath As String,
	compressionMethod As CompressionMethod,
	compressionLevel As CompressionLevel,
	extractionDirectory As String,
	silentExtraction As Boolean,
	overwriteFiles As ExtractExistingFileAction,
	deleteExtractedFilesAfterExtraction As Boolean,
	icon As String,
	windowTitle As String,
	windowStyle As SelfExtractorFlavor,
	commandLineArgument As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim sourceFileOrDir As String
Dim outputFilepath As String
Dim compressionMethod As CompressionMethod
Dim compressionLevel As CompressionLevel
Dim extractionDirectory As String
Dim silentExtraction As Boolean
Dim overwriteFiles As ExtractExistingFileAction
Dim deleteExtractedFilesAfterExtraction As Boolean
Dim icon As String
Dim windowTitle As String
Dim windowStyle As SelfExtractorFlavor
Dim commandLineArgument As String
Dim returnValue As String

returnValue = instance.BuildSfx(sourceFileOrDir, 
	outputFilepath, compressionMethod, 
	compressionLevel, extractionDirectory, 
	silentExtraction, overwriteFiles, 
	deleteExtractedFilesAfterExtraction, 
	icon, windowTitle, windowStyle, commandLineArgument)
```

**C++**<br />
``` C++
public:
String^ BuildSfx(
	String^ sourceFileOrDir, 
	String^ outputFilepath, 
	CompressionMethod compressionMethod, 
	CompressionLevel compressionLevel, 
	String^ extractionDirectory, 
	bool silentExtraction, 
	ExtractExistingFileAction overwriteFiles, 
	bool deleteExtractedFilesAfterExtraction, 
	String^ icon, 
	String^ windowTitle, 
	SelfExtractorFlavor windowStyle, 
	String^ commandLineArgument
)
```

**F#**<br />
``` F#
member BuildSfx : 
        sourceFileOrDir : string * 
        outputFilepath : string * 
        compressionMethod : CompressionMethod * 
        compressionLevel : CompressionLevel * 
        extractionDirectory : string * 
        silentExtraction : bool * 
        overwriteFiles : ExtractExistingFileAction * 
        deleteExtractedFilesAfterExtraction : bool * 
        icon : string * 
        windowTitle : string * 
        windowStyle : SelfExtractorFlavor * 
        commandLineArgument : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFileOrDir</dt><dd>Type: System.String<br />The source file or diretory.</dd><dt>outputFilepath</dt><dd>Type: System.String<br />The path of the output SFX file to create.</dd><dt>compressionMethod</dt><dd>Type: CompressionMethod<br />The compression method.</dd><dt>compressionLevel</dt><dd>Type: CompressionLevel<br />The compression level.</dd><dt>extractionDirectory</dt><dd>Type: System.String<br />The directory where to extract the SFX contents. 

 Default value is "`.\`" (the working directory path)</dd><dt>silentExtraction</dt><dd>Type: System.Boolean<br />A value indicating whether to perform a silent extraction.</dd><dt>overwriteFiles</dt><dd>Type: ExtractExistingFileAction<br />A value indicating whether to overwrite any existing file during the extraction.</dd><dt>deleteExtractedFilesAfterExtraction</dt><dd>Type: System.Boolean<br />A value indicating whether to delete the extracted files.</dd><dt>icon</dt><dd>Type: System.String<br />The icon for the SFX executable.</dd><dt>windowTitle</dt><dd>Type: System.String<br />The window title for the SFX executable.</dd><dt>windowStyle</dt><dd>Type: SelfExtractorFlavor<br />The window style of the SFX executable.</dd><dt>commandLineArgument</dt><dd>Type: System.String<br />The command-line arguments that will be passed to the SFX executable when ran.</dd></dl>

#### Return Value
Type: String<br />The full path of the resulting SFX file.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx">BuildSfx Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />