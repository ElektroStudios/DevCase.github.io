# GoogleSearch Class
 

Provides a way to use `Google Search` engine to crawl search results.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.Search.GoogleSearch<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class GoogleSearch : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class GoogleSearch
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearch
```

**C++**<br />
``` C++
public ref class GoogleSearch sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type GoogleSearch =  
    class
        inherit AestheticObject
    end
```

The GoogleSearch type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearch_GetSearchResult">GetSearchResult</a></td><td>
Searches the World Wide Web using `Google Search` service with the specified search options.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearch_GetSearchResultAsync">GetSearchResultAsync</a></td><td>
Asynchronously searches the World Wide Web using `Google Search` service with the specified search options.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearch_GetSearchResultString">GetSearchResultString</a></td><td>
Searches the World Wide Web using `Google Search` service with the specified search options.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearch_GetSearchResultStringAsync">GetSearchResultStringAsync</a></td><td>
Asynchronously searches the World Wide Web using `Google Search` service with the specified search options.</td></tr></table>&nbsp;
<a href="#googlesearch-class">Back to Top</a>

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
<a href="#googlesearch-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim searchOptions As New GoogleSearchOptions With {
    .SearchTerm = "Hello World",
    .Language = GoogleLanguage.EN,
    .NumberOfResults = GoogleSearchOptions.MaxNumberOfResults,
    .FilterResults = False,
    .InputEncoding = Encoding.GetEncoding("ISO-8859-1"),
    .OutputEncoding = Encoding.GetEncoding("ISO-8859-1")
}

Dim searchResults As List(Of GoogleSearchResult) = GoogleSearch.GetSearchResult(searchOptions)
Dim resultCount As Integer

For Each result As GoogleSearchResult In searchResults
    Console.WriteLine("[{0:000}] Url: {1}; Title: {2}; Description: {3}", Interlocked.Increment(resultCount), result.Url, result.Title, result.Description)
Next result

Console.WriteLine("Finished.")
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />