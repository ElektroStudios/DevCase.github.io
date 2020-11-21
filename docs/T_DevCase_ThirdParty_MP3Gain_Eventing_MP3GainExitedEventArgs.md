# MP3GainExitedEventArgs Class
 

Contains the event data of a <a href="E_DevCase_ThirdParty_MP3Gain_MP3GainWrapper_Exited">Exited</a> event.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticEventArgs">DevCase.Core.Design.AestheticEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.MP3Gain.Eventing.MP3GainExitedEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MP3GainExitedEventArgs : AestheticEventArgs
```

**VB**<br />
``` VB
Public NotInheritable Class MP3GainExitedEventArgs
	Inherits AestheticEventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainExitedEventArgs
```

**C++**<br />
``` C++
public ref class MP3GainExitedEventArgs sealed : public AestheticEventArgs
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MP3GainExitedEventArgs =  
    class
        inherit AestheticEventArgs
    end
```

The MP3GainExitedEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs__ctor">MP3GainExitedEventArgs</a></td><td>
Initializes a new instance of the MP3GainExitedEventArgs class.</td></tr></table>&nbsp;
<a href="#mp3gainexitedeventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_Arguments">Arguments</a></td><td>
Gets the arguments that was passed to the process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_ErrorMessage">ErrorMessage</a></td><td>
Gets the error messages (if any).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_ExitCode">ExitCode</a></td><td>
Gets the process exit code.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_File">File</a></td><td>
Gets the source audio filepath that was passed to the process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_GainLevel">GainLevel</a></td><td>
Gets the volume gain level change applied to file, in decibels. 

 This value is always `0` if performing a <a href="T_DevCase_ThirdParty_MP3Gain_MP3GainOperation">CheckTagInfo</a> task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_InfoMessage">InfoMessage</a></td><td>
Gets the information message of the realized task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs_Operation">Operation</a></td><td>
Gets the MP3Gain task that is being realized.</td></tr></table>&nbsp;
<a href="#mp3gainexitedeventargs-class">Back to Top</a>

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
<a href="#mp3gainexitedeventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing Namespace</a><br />