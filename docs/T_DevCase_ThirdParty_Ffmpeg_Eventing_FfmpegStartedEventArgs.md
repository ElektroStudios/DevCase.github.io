# FfmpegStartedEventArgs Class
 

Contains the event data of a <a href="E_DevCase_ThirdParty_Ffmpeg_Converter_Started">Started</a> event.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticEventArgs">DevCase.Core.Design.AestheticEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Ffmpeg.Eventing.FfmpegStartedEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class FfmpegStartedEventArgs : AestheticEventArgs
```

**VB**<br />
``` VB
Public NotInheritable Class FfmpegStartedEventArgs
	Inherits AestheticEventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As FfmpegStartedEventArgs
```

**C++**<br />
``` C++
public ref class FfmpegStartedEventArgs sealed : public AestheticEventArgs
```

**F#**<br />
``` F#
[<SealedAttribute>]
type FfmpegStartedEventArgs =  
    class
        inherit AestheticEventArgs
    end
```

The FfmpegStartedEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs__ctor">FfmpegStartedEventArgs</a></td><td>
Initializes a new instance of the FfmpegStartedEventArgs class.</td></tr></table>&nbsp;
<a href="#ffmpegstartedeventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs_File">File</a></td><td>
Gets the filepath that was passed as argument to the process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs_Task">Task</a></td><td>
Gets the <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">FfmpegTask</a> task that is being realized.</td></tr></table>&nbsp;
<a href="#ffmpegstartedeventargs-class">Back to Top</a>

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
<a href="#ffmpegstartedeventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing Namespace</a><br />