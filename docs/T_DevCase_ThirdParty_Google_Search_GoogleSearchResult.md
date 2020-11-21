# GoogleSearchResult Class
 

Represents a `Google Search` result.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.Search.GoogleSearchResult<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class GoogleSearchResult : AestheticObject
```

**VB**<br />
``` VB
Public Class GoogleSearchResult
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchResult
```

**C++**<br />
``` C++
public ref class GoogleSearchResult : public AestheticObject
```

**F#**<br />
``` F#
type GoogleSearchResult =  
    class
        inherit AestheticObject
    end
```

The GoogleSearchResult type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchResult__ctor">GoogleSearchResult(String, String, String)</a></td><td>
Initializes a new instance of the GoogleSearchResult class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchResult__ctor_1">GoogleSearchResult(String, Uri, String)</a></td><td>
Initializes a new instance of the GoogleSearchResult class.</td></tr></table>&nbsp;
<a href="#googlesearchresult-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchResult_Description">Description</a></td><td>
Gets the search result description.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchResult_Description_1">Description(Encoding, Encoding)</a></td><td>
Gets the search result description in the specified text encoding.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchResult_Title">Title</a></td><td>
Gets the search result title.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchResult_Title_1">Title(Encoding, Encoding)</a></td><td>
Gets the search result title in the specified text encoding.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Search_GoogleSearchResult_Url">Url</a></td><td>
Gets the search result Uri.</td></tr></table>&nbsp;
<a href="#googlesearchresult-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchResult_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Search_GoogleSearchResult_ToStringCsv">ToStringCsv</a></td><td>
Returns a String of comma-separated values (CSV) that represents this instance.</td></tr></table>&nbsp;
<a href="#googlesearchresult-class">Back to Top</a>

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
<a href="#googlesearchresult-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />