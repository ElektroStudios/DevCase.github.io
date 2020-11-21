# TranslateClient Class
 

A client for Google Translate service. 

 Note that Google Translate API is only available as a paid service, so, in order to use this class you need to enable billing for your project. For more info about see: http://cloud.google.com/translate/v2/quickstart 

 To use Google Translate services for free, see <a href="T_DevCase_Core_NET_Tools_GoogleTranslate">GoogleTranslate</a> class.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.Translate.TranslateClient<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class TranslateClient : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class TranslateClient
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As TranslateClient
```

**C++**<br />
``` C++
public ref class TranslateClient sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type TranslateClient =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The TranslateClient type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient__ctor">TranslateClient</a></td><td>
Initializes a new instance of the TranslateClient class.</td></tr></table>&nbsp;
<a href="#translateclient-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Translate_TranslateClient_ApiKey">ApiKey</a></td><td>
Gets the API key to use Google Translate service. 

 You can get an API key at Google's API Console: <a href="http://console.developers.google.com/apis" target="_blank">http://console.developers.google.com/apis</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Translate_TranslateClient_IsAuthorized">IsAuthorized</a></td><td>
Gets a value that determines whether Google Translate API authorization was done.</td></tr></table>&nbsp;
<a href="#translateclient-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_Authorize">Authorize</a></td><td>
Authorizes this instance to use Google Translate API service.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_AuthorizeAsync">AuthorizeAsync</a></td><td>
Asynchronously authorizes this instance to use Google Translate API service.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_TranslateHtml">TranslateHtml</a></td><td>
Translates the specified Html to the target language.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_TranslateHtmlAsync">TranslateHtmlAsync</a></td><td>
Asynchronously translates the specified text to the target language..</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_TranslateText">TranslateText</a></td><td>
Translates the specified text to the target language.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Translate_TranslateClient_TranslateTextAsync">TranslateTextAsync</a></td><td>
Asynchronously translates the specified text to the target language..</td></tr></table>&nbsp;
<a href="#translateclient-class">Back to Top</a>

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
<a href="#translateclient-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to translate text. 
**VB**<br />
``` VB
Dim client As New TranslateClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
Dim sourceText As String = "Hello World!"
Dim translatedText As String =  Await client.TranslateTextAsync(sourceText, GoogleTranslateLanguage.EN, GoogleTranslateLanguage.ES)
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Translate">DevCase.ThirdParty.Google.Translate Namespace</a><br />