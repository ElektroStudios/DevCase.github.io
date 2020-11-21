# YoutubeUrl Class
 

Represents a Youtube Url.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.YoutubeUrl<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class YoutubeUrl : AestheticObject
```

**VB**<br />
``` VB
Public Class YoutubeUrl
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeUrl
```

**C++**<br />
``` C++
public ref class YoutubeUrl : public AestheticObject
```

**F#**<br />
``` F#
type YoutubeUrl =  
    class
        inherit AestheticObject
    end
```

The YoutubeUrl type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_YoutubeUrl__ctor">YoutubeUrl(String)</a></td><td>
Initializes a new instance of the YoutubeUrl class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_YoutubeUrl__ctor_1">YoutubeUrl(Uri)</a></td><td>
Initializes a new instance of the YoutubeUrl class.</td></tr></table>&nbsp;
<a href="#youtubeurl-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_YoutubeUrl_PlaylistId">PlaylistId</a></td><td>
Gets the playlist Id.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_YoutubeUrl_Url">Url</a></td><td>
Gets the video Url.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_YoutubeUrl_VideoId">VideoId</a></td><td>
Gets the video Id.</td></tr></table>&nbsp;
<a href="#youtubeurl-class">Back to Top</a>

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
<a href="#youtubeurl-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim yUrl As New YoutubeUrl("http://www.youtube.com/watch?v=Hzmn4-vtl5M&feature=em-uploademail")

Console.WriteLine(yUrl.Url)
Console.WriteLine(yUrl.VideoId)
Console.WriteLine(yUrl.PlaylistId)
```


## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />