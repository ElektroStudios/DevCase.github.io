# CoreConverterProgressEventArgs Class
 

Contains the event data of a <a href="E_DevCase_ThirdParty_DBpoweramp_Converter_ProgressChanged">ProgressChanged</a> event.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticEventArgs">DevCase.Core.Design.AestheticEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.DBpoweramp.Eventing.CoreConverterProgressEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CoreConverterProgressEventArgs : AestheticEventArgs
```

**VB**<br />
``` VB
Public NotInheritable Class CoreConverterProgressEventArgs
	Inherits AestheticEventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As CoreConverterProgressEventArgs
```

**C++**<br />
``` C++
public ref class CoreConverterProgressEventArgs sealed : public AestheticEventArgs
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CoreConverterProgressEventArgs =  
    class
        inherit AestheticEventArgs
    end
```

The CoreConverterProgressEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs__ctor">CoreConverterProgressEventArgs</a></td><td>
Initializes a new instance of the CoreConverterProgressEventArgs class.</td></tr></table>&nbsp;
<a href="#coreconverterprogresseventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs_InputFile">InputFile</a></td><td>
Gets the filepath that was passed as argument to the process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs_OutputFile">OutputFile</a></td><td>
Gets the filepath of the file being converted.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs_Percent">Percent</a></td><td>
Gets the `CoreConverter.exe` task percent done.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs_Task">Task</a></td><td>
Gets the <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">CoreConverterTask</a> type that is being realized.</td></tr></table>&nbsp;
<a href="#coreconverterprogresseventargs-class">Back to Top</a>

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
<a href="#coreconverterprogresseventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing Namespace</a><br />