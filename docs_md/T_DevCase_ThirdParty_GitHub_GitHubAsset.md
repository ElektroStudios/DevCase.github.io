# GitHubAsset Class
 

Represents an asset of a release on GitHub.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.GitHub.GitHubAsset<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class GitHubAsset : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class GitHubAsset
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GitHubAsset
```

**C++**<br />
``` C++
public ref class GitHubAsset sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type GitHubAsset =  
    class
        inherit AestheticObject
    end
```

The GitHubAsset type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAsset__ctor">GitHubAsset</a></td><td>
Initializes a new instance of the GitHubAsset class.</td></tr></table>&nbsp;
<a href="#githubasset-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_ContentType">ContentType</a></td><td>
Gets the content-type of this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_DateCreated">DateCreated</a></td><td>
Gets the creation datetime.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_DateUploaded">DateUploaded</a></td><td>
Gets the uploaded datetime.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_DownloadCount">DownloadCount</a></td><td>
Gets a value indicating how many times this asset was downloaded.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_Id">Id</a></td><td>
Gets the GitHub's unique identifier for this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_Label">Label</a></td><td>
Gets the label of this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_Name">Name</a></td><td>
Gets the name of this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_Raw">Raw</a></td><td>
Gets the raw Xml content of this GitHubAsset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_Size">Size</a></td><td>
Gets the size of this asset, in bytes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_State">State</a></td><td>
Gets the state of this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_Uploader">Uploader</a></td><td>
Gets the uploader of this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_UriAsset">UriAsset</a></td><td>
Gets an Uri that points to the page of this asset.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAsset_UriDownload">UriDownload</a></td><td>
Gets an Uri that points to the download page of this asset.</td></tr></table>&nbsp;
<a href="#githubasset-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAsset_ToString">ToString</a></td><td>
Returns a String that represents this asset.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#githubasset-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAsset_op_Equality">Equality</a></td><td>
Implements the operator =.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAsset_op_Inequality">Inequality</a></td><td>
Implements the operator <>.</td></tr></table>&nbsp;
<a href="#githubasset-class">Back to Top</a>

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
<a href="#githubasset-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />

#### Other Resources
<a href="https://github.com" target="_blank">https://github.com</a><br />