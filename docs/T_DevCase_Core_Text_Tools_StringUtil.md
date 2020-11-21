# StringUtil Class
 

Contains String related utilties.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.Tools.StringUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class StringUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class StringUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As StringUtil
```

**C++**<br />
``` C++
public ref class StringUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type StringUtil =  
    class
        inherit AestheticObject
    end
```

The StringUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateLoremIpsumText">GenerateLoremIpsumText</a></td><td>
Generates a random 'Lorem Ipsum' paragraph.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateRandomParagraph">GenerateRandomParagraph</a></td><td>
Generates a random paragraph using the specified set of words.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString_2">GenerateRandomString(Int32)</a></td><td>
Generates a random alpha-numeric string of the specified length.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString">GenerateRandomString(Char[], Int32)</a></td><td>
Generates a random string of the specified length using the specified characters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString_3">GenerateRandomString(Int32, Int32)</a></td><td>
Generates a random alpha-numeric string within the specified string-length range.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateRandomString_1">GenerateRandomString(Char[], Int32, Int32)</a></td><td>
Generates a random string within the specified string-length range using the specified characters.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GenerateWhiteSpacedString">GenerateWhiteSpacedString</a></td><td>
Generates a white-spaced string with the specified length.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GetDiff">GetDiff</a></td><td>
Gets the character differences between two strings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GetDiffCount">GetDiffCount(String, String)</a></td><td>
Computes the total amount of differences (insertions, deletions or substitutions) between two strings, by using the Levenshtein algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GetDiffCount_1">GetDiffCount(String, String, Int32)</a></td><td>
Computes the total amount of differences (insertions, deletions or substitutions) between two strings, by using the Levenshtein algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Text_Tools_StringUtil_GetSimilarity">GetSimilarity</a></td><td>
Computes the similarity percentage between two strings, by using the Levenshtein algorithm.</td></tr></table>&nbsp;
<a href="#stringutil-class">Back to Top</a>

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
<a href="#stringutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />