# RegExUtil.Patterns Class
 

A class that exposes common RegEx patterns.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.RegEx.Tools.RegExUtil.Patterns<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class Patterns : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class Patterns
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegExUtil.Patterns
```

**C++**<br />
``` C++
public ref class Patterns sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Patterns =  
    class
        inherit AestheticObject
    end
```

The RegExUtil.Patterns type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_AlphabeticText">AlphabeticText</a></td><td>
A pattern that matches alphabetic text.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_AlphanumericText">AlphanumericText</a></td><td>
A pattern that matches Alphanumeric text.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_CreditCard">CreditCard</a></td><td>
A pattern that matches a valid credit card number, VISA or also a passport. 

 For Example:</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_EMail">EMail</a></td><td>
A pattern that matches an e-mail address. 

 For Example: 

`local@domain.com`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_ExcludeDashInFilename">ExcludeDashInFilename</a></td><td>
A pattern that matches any filename that does not contain a dash character (-). 

 For Example: 

 Match: `"Everybody.mp3"`

 Don't Match: `"Every-body.mp3"`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_ExcludeDashInString">ExcludeDashInString</a></td><td>
A pattern that matches any string that does not contain a dash character (-). 

 For Example: 

 Match: `"Everybody"`

 Don't Match: `"Every-body"`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_ExcludeUnderscoreInFilename">ExcludeUnderscoreInFilename</a></td><td>
A pattern that matches any filename that does not contain a underscore character (_). 

 For Example: 

 Match: `"Everybody.mp3"`

 Don't Match: `"Every_body.mp3"`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_ExcludeUnderscoreInString">ExcludeUnderscoreInString</a></td><td>
A pattern that matches any string that does not contain a underscore character (_). 

 For Example: 

 Match: `"Everybody"`

 Don't Match: `"Every_body"`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_Hex">Hex</a></td><td>
A pattern that matches Hexadecimal values. 

 For Example: 

`#a3c113`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_HtmlTag">HtmlTag</a></td><td>
A pattern that matches the content of an Html enclosed tag.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_Ipv4">Ipv4</a></td><td>
A pattern that matches an IPv4 address. 

 For Example: 

`127.0.0.1`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_Ipv6">Ipv6</a></td><td>
A pattern that matches an IPv6 address. 

 For Example: 

`FE80:0000:0000:0000:0202:B3FF:FE1E:8329`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_NumericText">NumericText</a></td><td>
A pattern that matches numeric text, integer or decimal.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_Phone">Phone</a></td><td>
A pattern that matches a Phone number. 

 Number in the following form: `(###) ###-####`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_SafeText">SafeText</a></td><td>
A pattern that matches lower and upper case letters and all digits. 

 For Example:</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_Url">Url</a></td><td>
A pattern that matches an URL. 

 For Example: 

`http://url` or `ftp://url`</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_USphone">USphone</a></td><td>
A pattern that matches an United States phone number with or without dashes. 

 For Example:</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_USssn">USssn</a></td><td>
A pattern that matches a 9 digit United States social security number with dashes. 

 For Example:</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_USzip">USzip</a></td><td>
A pattern that matches an United States zip code with optional dash-four. 

 For Example:</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Text_RegEx_Tools_RegExUtil_Patterns_YoutubeUrl">YoutubeUrl</a></td><td>
A pattern that matches a Youtube Url. 

 For Example: 

`https://www.youtube.com/watch?v=Hzmn4-vtl5M&feature=em-uploademail`

`http://www.youtube.com/attribution_link?a=Od7TH6HFkco&u=/watch?v%3DHzmn4-vtl5M%26feature%3Dem-uploademail`</td></tr></table>&nbsp;
<a href="#regexutil.patterns-class">Back to Top</a>

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
<a href="#regexutil.patterns-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Text_RegEx_Tools">DevCase.Core.Text.RegEx.Tools Namespace</a><br />