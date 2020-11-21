# CommandLineParameterCollection Class
 

Represents a strongly typed list of <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that can be accessed by an index.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.ObjectModel.Collection(<a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a>)<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticCollection_1">DevCase.Core.Design.AestheticCollection</a>(<a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a>)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.CommandLineParameterCollection<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("CommandLineParameterCollection")]
public class CommandLineParameterCollection : AestheticCollection<CommandLineParameter>
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("CommandLineParameterCollection")>
Public Class CommandLineParameterCollection
	Inherits AestheticCollection(Of CommandLineParameter)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameterCollection
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"CommandLineParameterCollection")]
public ref class CommandLineParameterCollection : public AestheticCollection<CommandLineParameter^>
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("CommandLineParameterCollection")>]
type CommandLineParameterCollection =  
    class
        inherit AestheticCollection<CommandLineParameter>
    end
```

The CommandLineParameterCollection type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection__ctor">CommandLineParameterCollection</a></td><td>
Initializes a new instance of the CommandLineParameterCollection class.</td></tr></table>&nbsp;
<a href="#commandlineparametercollection-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineParameterCollection_Item">Item</a></td><td>
Gets or sets the <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that matches the specified key name.</td></tr></table>&nbsp;
<a href="#commandlineparametercollection-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_Add">Add</a></td><td>
Adds a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> to the end of the CommandLineParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_AddRange">AddRange</a></td><td>
Adds the specified parameters to the end of the CommandLineParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_Contains">Contains</a></td><td>
Determines whether the CommandLineParameterCollection contains a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that matches the specified key name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_Find">Find</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that matches the specified parameter name, and returns the first occurrence within the entire CommandLineParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_IndexOf">IndexOf</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that matches the specified key name and returns the zero-based index of the first occurrence within the entire CommandLineParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_Remove_1">Remove(String)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> from the CommandLineParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineParameterCollection_Remove">Remove(CommandLineParameter)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> from the CommandLineParameterCollection.</td></tr></table>&nbsp;
<a href="#commandlineparametercollection-class">Back to Top</a>

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
<a href="#commandlineparametercollection-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />