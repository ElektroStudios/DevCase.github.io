# AlbumInfo Class
 

Represents the information of an album crawled with <a href="T_DevCase_ThirdParty_FHM_Crawler">Crawler</a>.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.FHM.AlbumInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class AlbumInfo : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class AlbumInfo
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As AlbumInfo
```

**C++**<br />
``` C++
public ref class AlbumInfo sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type AlbumInfo =  
    class
        inherit AestheticObject
    end
```

The AlbumInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_AlbumInfo__ctor">AlbumInfo</a></td><td>
Initializes a new instance of the AlbumInfo class.</td></tr></table>&nbsp;
<a href="#albuminfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Artist">Artist</a></td><td>
Gets the artist name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Country">Country</a></td><td>
Gets the country of the band/artist.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_DownloadLinks">DownloadLinks</a></td><td>
Gets the urls to download the album. It can be a single url, or multiple of them.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Genre">Genre</a></td><td>
Gets the music genre.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Id">Id</a></td><td>
Gets the album identifier (that is used in the 'sobiid' and 'sobi2id' parameters).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Title">Title</a></td><td>
Gets the album title.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Uri">Uri</a></td><td>
Gets the album <a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Uri">Uri</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_AlbumInfo_Year">Year</a></td><td>
Gets the year that the album has been released.</td></tr></table>&nbsp;
<a href="#albuminfo-class">Back to Top</a>

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
<a href="#albuminfo-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />