# ZipArchiver Class
 

A Zip file archiver.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.DotNetZip.ZipArchiver<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ZipArchiver : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class ZipArchiver
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
```

**C++**<br />
``` C++
public ref class ZipArchiver sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ZipArchiver =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The ZipArchiver type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver__ctor">ZipArchiver</a></td><td>
Initializes a new instance of the ZipArchiver class.</td></tr></table>&nbsp;
<a href="#ziparchiver-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build">Build(IEnumerable(String), String)</a></td><td>
Compresses the specified source files or diretories into a Zip archive using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_4">Build(String, String)</a></td><td>
Compresses the specified source file or diretory into a Zip archive using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_1">Build(IEnumerable(String), String, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source files or diretories into a Zip archive using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_2">Build(IEnumerable(String), String, String, EncryptionAlgorithm)</a></td><td>
Compresses the specified source files or diretories into a Zip archive, with a password, using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_5">Build(String, String, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source file or diretory into a Zip archive using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_6">Build(String, String, String, EncryptionAlgorithm)</a></td><td>
Compresses the specified source file or diretory into a Zip archive, with a password, using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_3">Build(IEnumerable(String), String, String, EncryptionAlgorithm, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source files or diretories into a Zip archive, with a password, using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Build_7">Build(String, String, String, EncryptionAlgorithm, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source file or diretory into a Zip archive, with a password, using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx">BuildSfx(IEnumerable(String), String)</a></td><td>
Compresses the specified source files or diretories into a self-extracting archive (SFX) using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_6">BuildSfx(String, String)</a></td><td>
Compresses the specified source file or diretory into a self-extracting archive (SFX) using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_1">BuildSfx(IEnumerable(String), String, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source files or diretories into a self-extracting archive (SFX) using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_3">BuildSfx(IEnumerable(String), String, String, EncryptionAlgorithm)</a></td><td>
Compresses the specified source files or diretories into a self-extracting archive (SFX), with a password, using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_7">BuildSfx(String, String, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source file or diretory into a self-extracting archive (SFX) using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_9">BuildSfx(String, String, String, EncryptionAlgorithm)</a></td><td>
Compresses the specified source file or diretory into a self-extracting archive (SFX), with a password, using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_4">BuildSfx(IEnumerable(String), String, String, EncryptionAlgorithm, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source files or diretories into a self-extracting archive (SFX), with a password, using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_10">BuildSfx(String, String, String, EncryptionAlgorithm, CompressionMethod, CompressionLevel)</a></td><td>
Compresses the specified source file or diretory into a self-extracting archive (SFX), with a password, using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_2">BuildSfx(IEnumerable(String), String, CompressionMethod, CompressionLevel, String, Boolean, ExtractExistingFileAction, Boolean, String, String, SelfExtractorFlavor, String)</a></td><td>
Compresses the specified source files or diretories into a self-extracting archive (SFX), using the specified compression and SFX parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_8">BuildSfx(String, String, CompressionMethod, CompressionLevel, String, Boolean, ExtractExistingFileAction, Boolean, String, String, SelfExtractorFlavor, String)</a></td><td>
Compresses the specified source file or diretory into a self-extracting archive (SFX), using the specified compression and SFX parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_5">BuildSfx(IEnumerable(String), String, String, EncryptionAlgorithm, CompressionMethod, CompressionLevel, String, Boolean, ExtractExistingFileAction, Boolean, String, String, SelfExtractorFlavor, String)</a></td><td>
Compresses the specified source files or diretories into a self-extracting archive (SFX), with a password, using the specified compression and SFX parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_BuildSfx_11">BuildSfx(String, String, String, EncryptionAlgorithm, CompressionMethod, CompressionLevel, String, Boolean, ExtractExistingFileAction, Boolean, String, String, SelfExtractorFlavor, String)</a></td><td>
Compresses the specified source file or diretory into a self-extracting archive (SFX), with a password, using the specified compression and SFX parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Extract">Extract(String, String, ExtractExistingFileAction)</a></td><td>
Extracts the contents of the source zip archive to the specified diretory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DotNetZip_ZipArchiver_Extract_1">Extract(String, String, ExtractExistingFileAction, String)</a></td><td>
Extracts the encrypted contents of the source zip archive to the specified diretory.</td></tr></table>&nbsp;
<a href="#ziparchiver-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_DotNetZip_ZipArchiver_CompressionProgressChanged">CompressionProgressChanged</a></td><td>
Occurs when the compression progress has changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_DotNetZip_ZipArchiver_ExtractionProgressChanged">ExtractionProgressChanged</a></td><td>
Occurs when the extraction progress has changed.</td></tr></table>&nbsp;
<a href="#ziparchiver-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#ziparchiver-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend WithEvents Archiver As New ZipArchiver

    Private Sub Test() Handles MyBase.Shown

        ' Build a Zip file.
        Archiver.Compress("C:\Source Folder", "C:\File.zip", CompressionMethod.None, CompressionLevel.Default, "Password", EncryptionAlgorithm.WinZipAes256)

        ' Build a SFX file.
        Archiver.CompressSfx("C:\Source Folder", "C:\File.exe", CompressionMethod.None, CompressionLevel.Default,
                             extractionDirectory:=".\", silentExtraction:=True, overwriteFiles:=ExtractExistingFileAction.DoNotOverwrite,
                             deleteExtractedFilesAfterExtraction:=False, commandLineArgument:=Nothing,
                             icon:=Nothing, windowTitle:="SFX Widnow Title", windowStyle:=SelfExtractorFlavor.WinFormsApplication)

        Archiver.Extract("C:\file.zip", "C:\dfsfdfsdf", ExtractExistingFileAction.DoNotOverwrite, "Password")

    End Sub

    Public Sub Archiver_CompressionProgressChanged(ByVal sender As Object, ByVal e As SaveProgressEventArgs) _
    Handles Archiver.CompressionProgressChanged

        Select Case e.EventType

            Case ZipProgressEventType.Saving_Started
                Console.WriteLine(String.Format("Begin creating file: {0}", e.ArchiveName))

            Case ZipProgressEventType.Saving_BeforeWriteEntry
                Console.WriteLine(String.Format("Writing ({1}/{2}): {0}",
                                                e.CurrentEntry.FileName,
                                                (e.EntriesSaved + 1),
                                                e.EntriesTotal))

                ' ProgressBar2.Maximum = e.EntriesTotal       ' Count of total files to compress.
                ' ProgressBar2.Value   = (e.EntriesSaved + 1) ' Count of compressed files.

            Case ZipProgressEventType.Saving_EntryBytesRead
                ' ProgressBar1.Value = CType((e.BytesTransferred * 100) / e.TotalBytesToTransfer, Integer) ' Total Progress.

            Case ZipProgressEventType.Saving_Completed
                Console.WriteLine(String.Format("Compression done: {0}", e.ArchiveName))

            Case Else
                ' ...

        End Select

    End Sub

    Public Sub Archiver_ExtractionProgressChanged(ByVal sender As Object, ByVal e As ExtractProgressEventArgs) _
    Handles Archiver.ExtractionProgressChanged

        Dim zipFileCount As Integer = DirectCast(sender, ZipFile).Entries.Count
        Static extractedFileCount As Integer

        Select Case e.EventType

            Case ZipProgressEventType.Extracting_BeforeExtractEntry
                If (extractedFileCount = 0) Then
                    Console.WriteLine(String.Format("Begin extracting file: {0}", e.ArchiveName))
                End If

                extractedFileCount += 1
                Console.WriteLine(String.Format("Extracting ({1}/{2}): {0}", e.CurrentEntry.FileName, extractedFileCount, zipFileCount))

                ' ProgressBar1.Maximum = zipFileCount       ' Count of total files to uncompress
                ' ProgressBar1.Value   = extractedFileCount ' Count of uncompressed files

            Case ZipProgressEventType.Extracting_AfterExtractEntry
                If (extractedFileCount = zipFileCount) Then
                    Console.WriteLine(String.Format("Extraction done: {0}", e.ArchiveName))
                End If

            Case Else
                ' ...

        End Select

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />