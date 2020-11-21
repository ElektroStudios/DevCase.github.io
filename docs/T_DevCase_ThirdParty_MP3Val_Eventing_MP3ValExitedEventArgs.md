# MP3ValExitedEventArgs Class
 

Contains the event data of a <a href="E_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Exited">Exited</a> event.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticEventArgs">DevCase.Core.Design.AestheticEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.MP3Val.Eventing.MP3ValExitedEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MP3ValExitedEventArgs : AestheticEventArgs
```

**VB**<br />
``` VB
Public NotInheritable Class MP3ValExitedEventArgs
	Inherits AestheticEventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValExitedEventArgs
```

**C++**<br />
``` C++
public ref class MP3ValExitedEventArgs sealed : public AestheticEventArgs
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MP3ValExitedEventArgs =  
    class
        inherit AestheticEventArgs
    end
```

The MP3ValExitedEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs__ctor">MP3ValExitedEventArgs</a></td><td>
Initializes a new instance of the MP3ValExitedEventArgs class.</td></tr></table>&nbsp;
<a href="#mp3valexitedeventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_Arguments">Arguments</a></td><td>
Gets the arguments that was passed to the process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_Errors">Errors</a></td><td>
Gets error messages (if any).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_ExitCode">ExitCode</a></td><td>
Gets the process exit code.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_File">File</a></td><td>
Gets the source audio filepath that was passed to the process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_FileIsFixed">FileIsFixed</a></td><td>
Gets a value indicating whether the source audio file was fixed. 

 This value is always `false` (`False` in Visual Basic) if not realizing a <a href="T_DevCase_ThirdParty_MP3Val_MP3ValTask">Fix</a> task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_FileNeedFix">FileNeedFix</a></td><td>
Gets a value indicating whether the source audio need to be fixed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_InfoMessage">InfoMessage</a></td><td>
Gets the info message of the realized task.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_Task">Task</a></td><td>
Gets the MP3Val task that is being realized.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs_Warnings">Warnings</a></td><td>
Gets warning messages (if any).</td></tr></table>&nbsp;
<a href="#mp3valexitedeventargs-class">Back to Top</a>

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
<a href="#mp3valexitedeventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing Namespace</a><br />