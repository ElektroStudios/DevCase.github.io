# GoogleTranslate Class
 

**Note: This API is now obsolete.**

A wrapper of the GoogleTranslate free API service to translate text into another language.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Tools.GoogleTranslate<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)]
public sealed class GoogleTranslate : AestheticObject
```

**VB**<br />
``` VB
<ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)>
Public NotInheritable Class GoogleTranslate
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleTranslate
```

**C++**<br />
``` C++
[ObsoleteAttribute(L"Google free API is now limited to few searchs. Use the paid API instead.", 
	true)]
public ref class GoogleTranslate sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ObsoleteAttribute("Google free API is now limited to few searchs. Use the paid API instead.", 
	true)>]
type GoogleTranslate =  
    class
        inherit AestheticObject
    end
```

The GoogleTranslate type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_GoogleTranslate_Translate">Translate</a></td><td> **Obsolete. **
Use GoogleTranslate service to translate the specified text into another language.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_GoogleTranslate_TranslateAsync">TranslateAsync</a></td><td> **Obsolete. **
Asynchronously use GoogleTranslate service to translate the specified text into another language.</td></tr></table>&nbsp;
<a href="#googletranslate-class">Back to Top</a>

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
<a href="#googletranslate-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />