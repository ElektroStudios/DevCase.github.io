# CommandLineParameter Class
 

Represents a command-line parameter that does not takes any value.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Application.CommandLineParameter<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">DevCase.Core.Application.CommandLineValueParameter(T)</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class CommandLineParameter
```

**VB**<br />
``` VB
Public Class CommandLineParameter
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameter
```

**C++**<br />
``` C++
public ref class CommandLineParameter
```

**F#**<br />
``` F#
type CommandLineParameter =  class end
```

The CommandLineParameter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameter__ctor">CommandLineParameter</a></td><td>
Initializes a new instance of the CommandLineParameter class.</td></tr></table>&nbsp;
<a href="#commandlineparameter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameter_FullName">FullName</a></td><td>
Gets the full name of the parameter including the prefix. 

 For Example: "/ParameterName"</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameter_FullShortName">FullShortName</a></td><td>
Gets the full short name of the parameter including the prefix. 

 For Example: "/ParameterShortName"</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameter_IsOptional">IsOptional</a></td><td>
Gets or sets a value indicating whether this parameter is required for the application. 

 A value of `false` (`False` in Visual Basic) means the user needs to pass this parameter to the application. 

 A value of `true` (`True` in Visual Basic) means this is an optional parameter so no matter if the user pass this parameter to the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameter_Name">Name</a></td><td>
Gets the name of the parameter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameter_Prefix">Prefix</a></td><td>
Gets or sets the prefix character that indicates the start of the parameter's name. 

 For example: "/ParameterName" where "/" is the prefix.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameter_ShortName">ShortName</a></td><td>
Gets or sets the short name of the parameter. 

 A short name should be an abbreviated name of the parameter. A short name is optional and can de null.</td></tr></table>&nbsp;
<a href="#commandlineparameter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameter_GetPrefixChar">GetPrefixChar</a></td><td>
Gets the prefix character that indicates the start of the parameter's name. 

 For Example: "/"</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameter_ToString">ToString</a></td><td>
Returns a String that represents this CommandLineParameter.</td></tr></table>&nbsp;
<a href="#commandlineparameter-class">Back to Top</a>

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
<a href="#commandlineparameter-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />