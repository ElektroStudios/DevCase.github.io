# GoogleSearchOptions Class
 

Represents the query parameters to use with `Google Search` engine.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.Search.GoogleSearchOptions<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class GoogleSearchOptions : AestheticObject, 
	ICloneable
```

**VB**<br />
``` VB
Public Class GoogleSearchOptions
	Inherits AestheticObject
	Implements ICloneable
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
```

**C++**<br />
``` C++
public ref class GoogleSearchOptions : public AestheticObject, 
	ICloneable
```

**F#**<br />
``` F#
type GoogleSearchOptions =  
    class
        inherit AestheticObject
        interface ICloneable
    end
```

The GoogleSearchOptions type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchOptions__ctor">GoogleSearchOptions</a></td><td>
Initializes a new instance of the GoogleSearchOptions class.</td></tr></table>&nbsp;
<a href="#googlesearchoptions-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_Filetype">Filetype</a></td><td>
Gets or sets a value that allows you to restrict search results to documents with a particular file extension. 

 Default value: {null}</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_FilterResults">FilterResults</a></td><td>
Gets or sets a value indicating whether to exclude similar website results from the search pages. 

 Default value: `false` (`False` in Visual Basic)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_InputEncoding">InputEncoding</a></td><td>
Gets or sets the input character encoding. 

 Default value: ISO-8859-1 (latin1)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_Language">Language</a></td><td>
Gets or sets a value to restrict search results to pages in the specified language. If there are no results In the specified language, the search appliance displays results In all languages. 

 Default value: <a href="T_DevCase_Core_NET_GoogleLanguage">Auto</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_NumberOfResults">NumberOfResults</a></td><td>
Gets or sets the number of search results to return. 

 The maximum allowed value is <a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxNumberOfResults">MaxNumberOfResults</a>. 

 Default value: `100`</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_OutputEncoding">OutputEncoding</a></td><td>
Gets or sets the output character encoding. 

 Default value: ISO-8859-1 (latin1)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_SearchTerm">SearchTerm</a></td><td>
Gets or sets the search query. Note that whitespaces are automatically separated by a plus (+) sign 

 Default value: {null}</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_Website">Website</a></td><td>
Gets or sets a value that allows you to restrict all search results should to a given site. 

 The specified value must contain less than <a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxWebsiteLength">MaxWebsiteLength</a> characters. 

 Default value: {null}</td></tr></table>&nbsp;
<a href="#googlesearchoptions-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_Clone">Clone</a></td><td>
Creates a new object that is a copy of the current instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_ToNameValueCollection">ToNameValueCollection</a></td><td>
Returns a NameValueCollection that represents the `Google` query for this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_ToString">ToString</a></td><td>
Returns a String that represents the `Google Search` GET request string for this instance.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#googlesearchoptions-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxNumberOfResults">MaxNumberOfResults</a></td><td>
The maximum number of search results to return.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxNumberOfResultsPerPage">MaxNumberOfResultsPerPage</a></td><td>
The maximum number of search results that can be included in one page.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxWebsiteLength">MaxWebsiteLength</a></td><td>
The maximum search results that can be included to documents in the specified domain, host or web directory.</td></tr></table>&nbsp;
<a href="#googlesearchoptions-class">Back to Top</a>

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
<a href="#googlesearchoptions-class">Back to Top</a>

## Remarks
<a href="http://www.google.com/support/enterprise/static/gsa/docs/admin/72/gsa_doc_set/xml_reference/request_format.html" target="_blank">http://www.google.com/support/enterprise/static/gsa/docs/admin/72/gsa_doc_set/xml_reference/request_format.html</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim searchOptions As New GoogleSearchOptions With {
    .SearchTerm = "Hello World",
    .Language = GoogleLanguage.EN,
    .NumberOfResults = GoogleSearchOptions.MaxNumberOfResults,
    .ExcludeSimilarResults = False,
    .StartPage = 0,
    .InputEncoding = Encoding.UTF8,
    .OutputEncoding = Encoding.GetEncoding("Windows-1252")
}

Dim searchResults As List(Of GoogleSearchResult) = GoogleSearch.GetSearchResult(searchOptions)
Dim resultCount As Integer

For Each result As GoogleSearchResult In searchResults
    Console.WriteLine("[{0:000}] Url: {1}; Title: {2}; Description: {3}", Interlocked.Increment(resultCount), result.Url, result.Title, result.Description)
Next result

Console.WriteLine("Done.")
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />