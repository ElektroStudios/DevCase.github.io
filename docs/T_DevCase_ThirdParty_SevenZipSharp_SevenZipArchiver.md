# SevenZipArchiver Class
 

A 7z file archiver.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">DevCase.ThirdParty.SevenZipSharp.Archiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SevenZipSharp.SevenZipArchiver<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SevenZipArchiver : Archiver
```

**VB**<br />
``` VB
Public NotInheritable Class SevenZipArchiver
	Inherits Archiver
```

**VB Usage**<br />
``` VB Usage
Dim instance As SevenZipArchiver
```

**C++**<br />
``` C++
public ref class SevenZipArchiver sealed : public Archiver
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SevenZipArchiver =  
    class
        inherit Archiver
    end
```

The SevenZipArchiver type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver__ctor">SevenZipArchiver(FileInfo)</a></td><td>
Initializes a new instance of the SevenZipArchiver class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver__ctor_1">SevenZipArchiver(String)</a></td><td>
Initializes a new instance of the SevenZipArchiver class.</td></tr></table>&nbsp;
<a href="#sevenziparchiver-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver_Build">Build(IEnumerable(String), String, CompressionMethod, CompressionLevel, Int32)</a></td><td>
Builds a compressed multi-volume archive containing the source files or directories using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver_Build_2">Build(String, String, CompressionMethod, CompressionLevel, Int32)</a></td><td>
Builds a compressed multi-volume archive containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver_Build_1">Build(IEnumerable(String), String, String, CompressionMethod, CompressionLevel, Int32)</a></td><td>
Builds a compressed multi-volume archive, with a password, containing the source files or directories using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver_Build_3">Build(String, String, String, CompressionMethod, CompressionLevel, Int32)</a></td><td>
Builds a compressed multi-volume archive, with a password, containing the source file or directory using the default compression parameters.</td></tr></table>&nbsp;
<a href="#sevenziparchiver-class">Back to Top</a>

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
<a href="#sevenziparchiver-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend WithEvents SevenZip As New SevenZipArchiver(".\7z64.dll")

    Private Sub Test() Handles MyBase.Shown

        ' Build a compressed file.
        SevenZip.Build("C:\Source Folder", "C:\File.7z", CompressionMethod.Lzma2, CompressionLevel.Normal)
        ' Add files into the compressed file.
        SevenZip.Add({"C:\File1.ext", "C:\File2.ext"}, "C:\File.7z", CompressionMethod.Lzma2, CompressionLevel.Normal)

        ' Build a multi-volume compressed file.
        SevenZip.Build("C:\Source Folder", "C:\Multi file.7z", CompressionMethod.Lzma2, CompressionLevel.Normal, 10000000)

        ' Build a SFX file.
        SevenZip.BuildSfx("C:\Source Folder", "C:\File.exe", SevenZipSharpSfxModule.WinExe, CompressionMethod.Lzma2, CompressionLevel.Normal)

        ' Extract the compressed files.
        SevenZip.Extract("C:\File.7z", "C:\Extracted")
        SevenZip.Extract("C:\Multi file.7z.001", "C:\Extracted Multi")
        SevenZip.Extract("C:\File.exe", "C:\Extracted SFX")

    End Sub

    Public Sub SevenZip_CompressionProgressChanged(ByVal sender As Object, ByVal e As SevenZip.ProgressEventArgs) _
    Handles SevenZip.CompressionProgressChanged

        Console.WriteLine(String.Format("Percent compressed: {0}%", e.PercentDone))

    End Sub

    Public Sub SevenZip_ExtractionProgressChanged(ByVal sender As Object, ByVal e As SevenZip.ProgressEventArgs) _
    Handles SevenZip.ExtractionProgressChanged

        Console.WriteLine(String.Format("Percent extracted: {0}%", e.PercentDone))

    End Sub

    Public Sub SevenZip_SfxCreated(ByVal sender As Object, ByVal e As String) _
    Handles SevenZip.SfxCreated

        Console.WriteLine(String.Format("SFX created: {0}", e))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />