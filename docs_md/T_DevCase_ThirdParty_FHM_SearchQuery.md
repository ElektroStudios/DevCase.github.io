# SearchQuery Class
 

Represents a search query of the http://freehardmusic.com/ website, that is managed by the <a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbums">FetchAlbums()</a> and <a href="M_DevCase_ThirdParty_FHM_Crawler_FetchAlbumsAsync">FetchAlbumsAsync()</a> methods. 

 Note that a search query can be performed in two different ways: 

 1. An artist-name based search (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a>). 

 2. A non-artist name based search. That is, a custom search based on country (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Country">Country</a>), genre (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Genre">Genre</a>) or year criterias (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Year">Year</a>); this kind of search can combine the three mentioned criterias, but not the artist name (<a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a>). 



 So, for an artist-name based search, the value of <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Country">Country</a>, <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Genre">Genre</a> and <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Year">Year</a> properties will always be set to "all". 



 And for a country, genre or year based search, the value of <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a> property will always be set to an empty string.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.FHM.SearchQuery<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SearchQuery : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class SearchQuery
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SearchQuery
```

**C++**<br />
``` C++
public ref class SearchQuery sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SearchQuery =  
    class
        inherit AestheticObject
    end
```

The SearchQuery type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_SearchQuery__ctor">SearchQuery(String)</a></td><td>
Initializes a new instance of the SearchQuery class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_SearchQuery__ctor_1">SearchQuery(String, String, String)</a></td><td>
Initializes a new instance of the SearchQuery class.</td></tr></table>&nbsp;
<a href="#searchquery-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_SearchQuery_Artist">Artist</a></td><td>
Gets or sets the artist name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_SearchQuery_Country">Country</a></td><td>
Gets or sets the country of the band/artist.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_SearchQuery_Genre">Genre</a></td><td>
Gets or sets the music genre.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_SearchQuery_Uri">Uri</a></td><td>
Gets the <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Uri">Uri</a> that represents this search query.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_SearchQuery_Uri_1">Uri(Int32)</a></td><td>
Gets the <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Uri">Uri</a> that represents this search query.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_FHM_SearchQuery_Year">Year</a></td><td>
Gets or sets the year that the album has been released.</td></tr></table>&nbsp;
<a href="#searchquery-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_SearchQuery_Reset">Reset</a></td><td>
Resets the current search query to its default values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FHM_SearchQuery_ToString">ToString</a></td><td>
Returns a String that represents the search query.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#searchquery-class">Back to Top</a>

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
<a href="#searchquery-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />