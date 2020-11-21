# Archiver Class
 

The base class of SevenZipSharp for compressed file archivers.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SevenZipSharp.Archiver<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#inheritance-hierarchy">More...</a>
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public abstract class Archiver : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public MustInherit Class Archiver
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
```

**C++**<br />
``` C++
public ref class Archiver abstract : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
type Archiver =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The Archiver type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver__ctor">Archiver(OutArchiveFormat, FileInfo)</a></td><td>
Initializes a new instance of the Archiver class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver__ctor_1">Archiver(OutArchiveFormat, String)</a></td><td>
Initializes a new instance of the Archiver class.</td></tr></table>&nbsp;
<a href="#archiver-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add">Add(IEnumerable(String), String)</a></td><td>
Appends the source file or directory into the specified compressed archive using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_4">Add(String, String)</a></td><td>
Appends the source file or directory into the specified compressed archive using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_2">Add(IEnumerable(String), String, String)</a></td><td>
Appends the source file or directory into the specified compressed archive, with a password, using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_6">Add(String, String, String)</a></td><td>
Appends the source file or directory into the specified compressed archive, with a password, using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_1">Add(IEnumerable(String), String, CompressionMethod, CompressionLevel)</a></td><td>
Appends the source file or directory into the specified compressed archive using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_5">Add(String, String, CompressionMethod, CompressionLevel)</a></td><td>
Appends the source file or directory into the specified compressed archive using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_3">Add(IEnumerable(String), String, String, CompressionMethod, CompressionLevel)</a></td><td>
Appends the source file or directory into the specified compressed archive, with a password, using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Add_7">Add(String, String, String, CompressionMethod, CompressionLevel)</a></td><td>
Appends the source file or directory into the specified compressed archive, with a password, using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build">Build(IEnumerable(String), String)</a></td><td>
Builds a compressed archive containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_4">Build(String, String)</a></td><td>
Builds a compressed archive containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_2">Build(IEnumerable(String), String, String)</a></td><td>
Builds a compressed archive, with a password, containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_6">Build(String, String, String)</a></td><td>
Builds a compressed archive, with a password, containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_1">Build(IEnumerable(String), String, CompressionMethod, CompressionLevel)</a></td><td>
Builds a compressed archive containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_5">Build(String, String, CompressionMethod, CompressionLevel)</a></td><td>
Builds a compressed archive containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_3">Build(IEnumerable(String), String, String, CompressionMethod, CompressionLevel)</a></td><td>
Builds a compressed archive, with a password, containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Build_7">Build(String, String, String, CompressionMethod, CompressionLevel)</a></td><td>
Builds a compressed archive, with a password, containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx">BuildSfx(IEnumerable(String), String, SevenZipSharpSfxModule)</a></td><td>
Builds a self-extracting archive (SFX) containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_4">BuildSfx(String, String, SevenZipSharpSfxModule)</a></td><td>
Builds a self-extracting archive (SFX) containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_2">BuildSfx(IEnumerable(String), String, String, SevenZipSharpSfxModule)</a></td><td>
Builds a self-extracting archive (SFX), with a password, containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_6">BuildSfx(String, String, String, SevenZipSharpSfxModule)</a></td><td>
Builds a self-extracting archive (SFX), with a password, containing the source file or directory using the default compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_1">BuildSfx(IEnumerable(String), String, SevenZipSharpSfxModule, CompressionMethod, CompressionLevel)</a></td><td>
Builds a self-extracting archive (SFX) containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_5">BuildSfx(String, String, SevenZipSharpSfxModule, CompressionMethod, CompressionLevel)</a></td><td>
Builds a self-extracting archive (SFX) containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_3">BuildSfx(IEnumerable(String), String, String, SevenZipSharpSfxModule, CompressionMethod, CompressionLevel)</a></td><td>
Builds a self-extracting archive (SFX), with a password, containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_BuildSfx_7">BuildSfx(String, String, String, SevenZipSharpSfxModule, CompressionMethod, CompressionLevel)</a></td><td>
Builds a self-extracting archive (SFX), with a password, containing the source file or directory using the specified compression parameters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Extract">Extract(String, String)</a></td><td>
Extracts the contents of the source compressed archive to the specified diretory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_SevenZipSharp_Archiver_Extract_1">Extract(String, String, String)</a></td><td>
Extracts the contents of the source compressed archive encrypted with a password, to the specified diretory.</td></tr></table>&nbsp;
<a href="#archiver-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_SevenZipSharp_Archiver_CompressionProgressChanged">CompressionProgressChanged</a></td><td>
Occurs when the compression progress has changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_SevenZipSharp_Archiver_ExtractionProgressChanged">ExtractionProgressChanged</a></td><td>
Occurs when the extraction progress has changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_SevenZipSharp_Archiver_SfxCreated">SfxCreated</a></td><td>
Occurs when a SFX is created.</td></tr></table>&nbsp;
<a href="#archiver-class">Back to Top</a>

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
<a href="#archiver-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />

## Inheritance HierarchySystem.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SevenZipSharp.Archiver<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_BZipArchiver">DevCase.ThirdParty.SevenZipSharp.BZipArchiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_GZipArchiver">DevCase.ThirdParty.SevenZipSharp.GZipArchiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_SevenZipArchiver">DevCase.ThirdParty.SevenZipSharp.SevenZipArchiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_TarArchiver">DevCase.ThirdParty.SevenZipSharp.TarArchiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_XZArchiver">DevCase.ThirdParty.SevenZipSharp.XZArchiver</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SevenZipSharp_ZipArchiver">DevCase.ThirdParty.SevenZipSharp.ZipArchiver</a><br />