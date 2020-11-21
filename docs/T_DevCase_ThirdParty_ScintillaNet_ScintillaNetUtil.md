# ScintillaNetUtil Class
 

Contains ScintillaNet related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.ScintillaNet.ScintillaNetUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ScintillaNet">DevCase.ThirdParty.ScintillaNet</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ScintillaNetUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ScintillaNetUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ScintillaNetUtil
```

**C++**<br />
``` C++
public ref class ScintillaNetUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ScintillaNetUtil =  
    class
        inherit AestheticObject
    end
```

The ScintillaNetUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_AddLineNumbers">AddLineNumbers</a></td><td>
Adds line numbers on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_DisableControlKeysPrint">DisableControlKeysPrint</a></td><td>
Supress the print-code for the Control keys pressed in the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_EnableControlKeysPrint">EnableControlKeysPrint</a></td><td>
Enables the print-code for the Control keys pressed in the specified Scintilla editor that were previously disabled by calling <a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_DisableControlKeysPrint">DisableControlKeysPrint(Scintilla)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_RemoveLineNumbers">RemoveLineNumbers(Scintilla, Int32)</a></td><td>
Removes the line numbers on the specified Scintilla editor that were previously added by calling <a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_AddLineNumbers">AddLineNumbers(Scintilla, Int32)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_RemoveLineNumbers_1">RemoveLineNumbers(Scintilla, Int32, Int32)</a></td><td>
Removes the line numbers on the specified Scintilla editor that were previously added by calling <a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_AddLineNumbers">AddLineNumbers(Scintilla, Int32)</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetCSharpDarkStyle">SetCSharpDarkStyle</a></td><td>
Sets a C# dark lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetCSharpLightStyle">SetCSharpLightStyle</a></td><td>
Sets a C# light lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetCSharpSystemStyle">SetCSharpSystemStyle</a></td><td>
Sets a C# system-default lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetPythonLightStyle">SetPythonLightStyle</a></td><td>
Sets a Python light lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetVbNetDarkStyle">SetVbNetDarkStyle</a></td><td>
Sets a VisualBasic.Net dark lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetVbNetLightStyle">SetVbNetLightStyle</a></td><td>
Sets a VisualBasic.Net light lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetVbNetSystemStyle">SetVbNetSystemStyle</a></td><td>
Sets a VisualBasic.Net system-default lexer style on the specified Scintilla editor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_SetXmlLightStyle">SetXmlLightStyle</a></td><td>
Sets a Xml light lexer style on the specified Scintilla editor.</td></tr></table>&nbsp;
<a href="#scintillanetutil-class">Back to Top</a>

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
<a href="#scintillanetutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_ScintillaNet">DevCase.ThirdParty.ScintillaNet Namespace</a><br />