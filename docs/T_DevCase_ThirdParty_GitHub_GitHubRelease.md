# GitHubRelease Class
 

Represents a release on GitHub.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.GitHub.GitHubRelease<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class GitHubRelease : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class GitHubRelease
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GitHubRelease
```

**C++**<br />
``` C++
public ref class GitHubRelease sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type GitHubRelease =  
    class
        inherit AestheticObject
    end
```

The GitHubRelease type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubRelease__ctor">GitHubRelease</a></td><td>
Initializes a new instance of the GitHubRelease class.</td></tr></table>&nbsp;
<a href="#githubrelease-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Assets">Assets</a></td><td>
Gets the assets of this release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Author">Author</a></td><td>
Gets the author of this release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Body">Body</a></td><td>
Gets the body, in MarkDown format.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_DateCreated">DateCreated</a></td><td>
Gets the creation datetime.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_DatePublished">DatePublished</a></td><td>
Gets the published datetime.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Id">Id</a></td><td>
Gets the GitHub's unique identifier for this release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_IsDraft">IsDraft</a></td><td>
Gets a value that determine whether this release is a draft.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_IsPreRelease">IsPreRelease</a></td><td>
Gets a value that determine whether this release is a pre-release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Name">Name</a></td><td>
Gets the release name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Raw">Raw</a></td><td>
Gets the raw Xml content of this GitHubRelease.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_TagName">TagName</a></td><td>
Gets the release tag name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_TargetCommitish">TargetCommitish</a></td><td>
Gets the commition target.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_UriAssets">UriAssets</a></td><td>
Gets an Uri that points to the assets page of this release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_UriHtml">UriHtml</a></td><td>
Gets an Uri that points to the release page for a web-browser.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_UriRelease">UriRelease</a></td><td>
Gets an Uri that points to the release page.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_UriTarball">UriTarball</a></td><td>
Gets an Uri that points to the tarball file of this release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_UriZipball">UriZipball</a></td><td>
Gets an Uri that points to the zipball file of this release.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_GitHub_GitHubRelease_Version">Version</a></td><td>
Gets the release version.</td></tr></table>&nbsp;
<a href="#githubrelease-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubRelease_ToString">ToString</a></td><td>
Returns a String that represents this release.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#githubrelease-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubRelease_op_Equality">Equality</a></td><td>
Implements the operator =.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_GitHub_GitHubRelease_op_Inequality">Inequality</a></td><td>
Implements the operator <>.</td></tr></table>&nbsp;
<a href="#githubrelease-class">Back to Top</a>

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
<a href="#githubrelease-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_GitHub">DevCase.ThirdParty.GitHub Namespace</a><br />

#### Other Resources
<a href="https://github.com" target="_blank">https://github.com</a><br />