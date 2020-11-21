# GitHubAuthor Class
 

Represents the author of a release or the uploader of an asset on GitHub.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.GitHub.GitHubAuthor<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class GitHubAuthor : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class GitHubAuthor
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GitHubAuthor
```

**C++**<br />
``` C++
public ref class GitHubAuthor sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type GitHubAuthor =  
    class
        inherit AestheticObject
    end
```

The GitHubAuthor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAuthor__ctor">GitHubAuthor</a></td><td>
Initializes a new instance of the GitHubAuthor class.</td></tr></table>&nbsp;
<a href="#githubauthor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_GravatarId">GravatarId</a></td><td>
Gets the unique identifier of the Gravatar. 

 See for more info: <a href="https://gravatar.com/" target="_blank">https://gravatar.com/</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_Id">Id</a></td><td>
Gets the GitHub's unique identifier for this author.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_IsSiteAdministrator">IsSiteAdministrator</a></td><td>
Gets a value that determine whether this author is a site administrator.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_Name">Name</a></td><td>
Gets the author name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_Raw">Raw</a></td><td>
Gets the raw Xml content of this GitHubAuthor.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_Type">Type</a></td><td>
Gets the type of user.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriAuthor">UriAuthor</a></td><td>
Gets an Uri that points to the author page.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriAvatar">UriAvatar</a></td><td>
Gets an Uri that points to the avatar page of this author.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriFollowers">UriFollowers</a></td><td>
Gets an Uri that points to the followers page of this author.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriHtml">UriHtml</a></td><td>
Gets an Uri that points to the author page for a web-browser.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriOrganizations">UriOrganizations</a></td><td>
Gets an Uri that points to the organizations page of this author.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriReceivedEvents">UriReceivedEvents</a></td><td>
Gets an Uri that points to the received events page of this author.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriRepositories">UriRepositories</a></td><td>
Gets an Uri that points to the repositories page of this author.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubAuthor_UriSubscriptions">UriSubscriptions</a></td><td>
Gets an Uri that points to the subscriptions page of this author.</td></tr></table>&nbsp;
<a href="#githubauthor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAuthor_ToString">ToString</a></td><td>
Returns a String that represents this author.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#githubauthor-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAuthor_op_Equality">Equality</a></td><td>
Implements the operator =.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubAuthor_op_Inequality">Inequality</a></td><td>
Implements the operator <>.</td></tr></table>&nbsp;
<a href="#githubauthor-class">Back to Top</a>

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
<a href="#githubauthor-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />

#### Other Resources
<a href="https://github.com" target="_blank">https://github.com</a><br />