# StereoVolume Structure
 

Defines a volume level from range 0 to 100 for left and right stereo channels.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("StereoVolume")]
public struct StereoVolume
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("StereoVolume")>
Public Structure StereoVolume
```

**VB Usage**<br />
``` VB Usage
Dim instance As StereoVolume
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"StereoVolume")]
public value class StereoVolume
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("StereoVolume")>]
type StereoVolume =  struct end
```

The StereoVolume type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_StereoVolume__ctor">StereoVolume</a></td><td>
Initializes a new instance of the StereoVolume structure.</td></tr></table>&nbsp;
<a href="#stereovolume-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_StereoVolume_LeftChannel">LeftChannel</a></td><td>
Gets the left channel volume, from range 0 to 100.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_StereoVolume_RightChannel">RightChannel</a></td><td>
Gets the right channel volume, from range 0 to 100.</td></tr></table>&nbsp;
<a href="#stereovolume-structure">Back to Top</a>

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
<a href="#stereovolume-structure">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />