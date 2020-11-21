# ZipArchiver Class
 

A Zip file archiver.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">DevCase.ThirdParty.SevenZipSharp.Archiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SevenZipSharp.ZipArchiver<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ZipArchiver : Archiver
```

**VB**<br />
``` VB
Public NotInheritable Class ZipArchiver
	Inherits Archiver
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
```

**C++**<br />
``` C++
public ref class ZipArchiver sealed : public Archiver
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ZipArchiver =  
    class
        inherit Archiver
    end
```

The ZipArchiver type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_ZipArchiver__ctor">ZipArchiver(FileInfo)</a></td><td>
Initializes a new instance of the ZipArchiver class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_ZipArchiver__ctor_1">ZipArchiver(String)</a></td><td>
Initializes a new instance of the ZipArchiver class.</td></tr></table>&nbsp;
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
    Friend WithEvents Archiver As New ZipArchiver(".\7z64.dll")

    Private Sub Test() Handles MyBase.Shown

        ' Build a compressed file.
        Archiver.Build("C:\Source Folder", "C:\File.7z", CompressionMethod.Lzma2, CompressionLevel.Normal)

        ' Add files into the compressed file.
         Archiver.Add({"C:\File1.ext", "C:\File2.ext"}, "C:\File.7z", CompressionMethod.Lzma2, CompressionLevel.Normal)

        ' Build a SFX file.
        Archiver.BuildSfx("C:\Source Folder", "C:\File.exe", SevenZipSharpSfxModule.WinExe, CompressionMethod.Lzma2, CompressionLevel.Normal)

        ' Extract the compressed files.
        Archiver.Extract("C:\File.7z", "C:\Extracted")
        Archiver.Extract("C:\File.exe", "C:\Extracted SFX")

    End Sub

    Public Sub SevenZip_CompressionProgressChanged(ByVal sender As Object, ByVal e As SevenZip.ProgressEventArgs) _
    Handles Archiver.CompressionProgressChanged

        Console.WriteLine(String.Format("Percent compressed: {0}%", e.PercentDone))

    End Sub

    Public Sub SevenZip_ExtractionProgressChanged(ByVal sender As Object, ByVal e As SevenZip.ProgressEventArgs) _
    Handles Archiver.ExtractionProgressChanged

        Console.WriteLine(String.Format("Percent extracted: {0}%", e.PercentDone))

    End Sub

    Public Sub SevenZip_SfxCreated(ByVal sender As Object, ByVal e As String) _
    Handles Archiver.SfxCreated

        Console.WriteLine(String.Format("SFX created: {0}", e))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />