# YoutubeClient Class
 

A client for Youtube services.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.Youtube.YoutubeClient<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class YoutubeClient : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class YoutubeClient
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
```

**C++**<br />
``` C++
public ref class YoutubeClient sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type YoutubeClient =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The YoutubeClient type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient__ctor">YoutubeClient(String, MailAddress, YoutubeScopes)</a></td><td>
Initializes a new instance of the YoutubeClient class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient__ctor_1">YoutubeClient(String, String, YoutubeScopes)</a></td><td>
Initializes a new instance of the YoutubeClient class.</td></tr></table>&nbsp;
<a href="#youtubeclient-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Youtube_YoutubeClient_IsAuthorized">IsAuthorized</a></td><td>
Gets a value that determines whether Youtube API authorization was done.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Youtube_YoutubeClient_MailAddress">MailAddress</a></td><td>
Gets the mail address to authorize Youtube service. (e.g: "yourmail@gmail.com")</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Youtube_YoutubeClient_Scopes">Scopes</a></td><td>
Gets the current Youtube OAuthv2 scopes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Youtube_YoutubeClient_Secrets">Secrets</a></td><td>
Gets the client credentials.</td></tr></table>&nbsp;
<a href="#youtubeclient-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_Authorize">Authorize</a></td><td>
Authorizes this instance to use Youtube API services.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_AuthorizeAsync">AuthorizeAsync</a></td><td>
Authorizes this instance to use Youtube API services.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_GetMySubscriptions">GetMySubscriptions</a></td><td>
Gets a list containing the subscriptions of the current youtube account.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_GetMyUploads">GetMyUploads</a></td><td>
Gets a list containing the videos uploaded in the current youtube account.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_GetVideos">GetVideos</a></td><td>
Gets a list containing the videos uploaded in the specified channel.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_SearchChannels">SearchChannels</a></td><td>
Searchs channels through Youtube that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_SearchPlaylists">SearchPlaylists</a></td><td>
Searchs playlists through Youtube that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Youtube_YoutubeClient_SearchVideos">SearchVideos</a></td><td>
Searchs videos through Youtube that matches the specified criteria.</td></tr></table>&nbsp;
<a href="#youtubeclient-class">Back to Top</a>

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
<a href="#youtubeclient-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to search videos by a search-pattern through Youtube. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com", YoutubeScopes.Youtube)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim videos As List(Of SearchResult) = Await client.SearchVideos("Rihanna", VideoDefinitionEnum.High, OrderEnum.Relevance)
Dim videoCount As Integer

For Each video As SearchResult In videos
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(videoCount),
                              video.Id.VideoId, video.Snippet.Title,
                              String.Format("http://www.youtube.com/watch?v={0}", video.Id.VideoId)))

Next video
```


## Examples
This is a code example that demonstrates how to get the uploaded videos from a channel. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com", YoutubeScopes.Youtube)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim videos As List(Of PlaylistItem) = Await client.GetVideos(channelId:="UC2xskkQVFEpLcGFnNSLQY0A") ' RihannaVEVO channel.
Dim videoCount As Integer

For Each video As PlaylistItem In videos
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(videoCount),
                              video.Id, video.Snippet.Title,
                              String.Format("http://www.youtube.com/watch?v={0}", video.Snippet.ResourceId.VideoId)))

Next video
```


## Examples
This is a code example that demonstrates how to get the uploaded videos from the current logged account. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com", YoutubeScopes.Youtube)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim videos As List(Of PlaylistItem) = Await client.GetMyUploads()
Dim videoCount As Integer

For Each video As PlaylistItem In videos
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(videoCount),
                              video.Id, video.Snippet.Title,
                              String.Format("http://www.youtube.com/watch?v={0}", video.Snippet.ResourceId.VideoId)))

Next video
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />