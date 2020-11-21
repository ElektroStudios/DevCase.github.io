# SharpDXUtil Class
 

Contains SharpDX related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.SharpDX.SharpDXUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SharpDXUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class SharpDXUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SharpDXUtil
```

**C++**<br />
``` C++
public ref class SharpDXUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SharpDXUtil =  
    class
        inherit AestheticObject
    end
```

The SharpDXUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_SharpDX_SharpDXUtil_TakeScreenshot">TakeScreenshot(Boolean)</a></td><td>
Capture the screen output using the default graphics card adapter. 

 This DirectX based methodology is useful to take screenshot of games that are running in full screen. 

 However, using this methodology for other common desktop screen captures will produce unexpected results (such as wrong colors); so for common screenshots you should use the methods exposed in <a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil</a> instead.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_SharpDX_SharpDXUtil_TakeScreenshot_1">TakeScreenshot(Int32, Boolean)</a></td><td>
Captures the screen output using the specified graphics card adapter. 

 This DirectX based methodology is useful to take screenshot of games that are running in full screen. 

 However, using this methodology for other common desktop screen captures will produce unexpected results (such as wrong colors); so for common screenshots you should use the methods exposed in <a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil</a> instead.</td></tr></table>&nbsp;
<a href="#sharpdxutil-class">Back to Top</a>

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
<a href="#sharpdxutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />