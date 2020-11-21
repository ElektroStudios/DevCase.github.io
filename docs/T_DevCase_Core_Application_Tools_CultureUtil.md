# CultureUtil Class
 

Contains application related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Tools.CultureUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CultureUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class CultureUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As CultureUtil
```

**C++**<br />
``` C++
public ref class CultureUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CultureUtil =  
    class
        inherit AestheticObject
    end
```

The CultureUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Tools_CultureUtil_CurrentCulture">CurrentCulture</a></td><td>
Gets the UI culture of the current thread.</td></tr></table>&nbsp;
<a href="#cultureutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_GetProcessPreferredUILanguages">GetProcessPreferredUILanguages</a></td><td>
Retrieves the preferred UI languages for the current process. 

 To set the preferred UI languages for the current process, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_SetProcessPreferredUILanguages">SetProcessPreferredUILanguages(CultureInfo[])</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_GetSystemPreferredUILanguages">GetSystemPreferredUILanguages</a></td><td>
Retrieves the preferred UI languages for the operating system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_GetThreadPreferredUILanguages">GetThreadPreferredUILanguages</a></td><td>
Retrieves the preferred UI languages for the current thread. 

 To set the preferred UI languages for the current thread, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_SetThreadPreferredUILanguages">SetThreadPreferredUILanguages(CultureInfo[])</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_SetCurrentCulture">SetCurrentCulture(CultureInfo)</a></td><td>
Sets the culture of the current thread.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_SetCurrentCulture_1">SetCurrentCulture(String)</a></td><td>
Sets the culture of the current thread.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_SetProcessPreferredUILanguages">SetProcessPreferredUILanguages(CultureInfo[])</a></td><td>
Sets the preferred UI languages for the current process. 

 To retrieve the preferred UI languages for the current process, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetProcessPreferredUILanguages">GetProcessPreferredUILanguages()</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_SetProcessPreferredUILanguages_1">SetProcessPreferredUILanguages(String[])</a></td><td>
Sets the preferred UI languages for the current process. 

 To retrieve the preferred UI languages for the current process, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetProcessPreferredUILanguages">GetProcessPreferredUILanguages()</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_SetThreadPreferredUILanguages">SetThreadPreferredUILanguages(CultureInfo[])</a></td><td>
Sets the preferred UI languages for the current thread. 

 To retrieve the preferred UI languages for the current thread, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetThreadPreferredUILanguages">GetThreadPreferredUILanguages()</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Tools_CultureUtil_SetThreadPreferredUILanguages_1">SetThreadPreferredUILanguages(String[])</a></td><td>
Sets the preferred UI languages for the current thread. 

 To retrieve the preferred UI languages for the current thread, call <a href="M_DevCase_Core_Application_Tools_CultureUtil_GetThreadPreferredUILanguages">GetThreadPreferredUILanguages()</a> function.</td></tr></table>&nbsp;
<a href="#cultureutil-class">Back to Top</a>

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
<a href="#cultureutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />