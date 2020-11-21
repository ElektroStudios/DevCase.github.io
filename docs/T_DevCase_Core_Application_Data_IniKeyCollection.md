# IniKeyCollection Class
 

Represents a strongly typed list of <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that can be accessed by an index.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.ObjectModel.Collection(<a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a>)<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticCollection_1">DevCase.Core.Design.AestheticCollection</a>(<a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a>)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Data.IniKeyCollection<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("IniKeyCollection")]
public sealed class IniKeyCollection : AestheticCollection<IniKey>
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("IniKeyCollection")>
Public NotInheritable Class IniKeyCollection
	Inherits AestheticCollection(Of IniKey)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"IniKeyCollection")]
public ref class IniKeyCollection sealed : public AestheticCollection<IniKey^>
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("IniKeyCollection")>]
type IniKeyCollection =  
    class
        inherit AestheticCollection<IniKey>
    end
```

The IniKeyCollection type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection__ctor">IniKeyCollection</a></td><td>
Initializes a new instance of the IniKeyCollection class.</td></tr></table>&nbsp;
<a href="#inikeycollection-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_IniKeyCollection_Item">Item</a></td><td>
Gets or sets the <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name.</td></tr></table>&nbsp;
<a href="#inikeycollection-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_Add">Add(IniKey)</a></td><td>
Adds a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> to the end of the IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_Add_1">Add(String, String, String)</a></td><td>
Adds a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> to the end of the IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_AddRange_1">AddRange(String[])</a></td><td>
Adds the specified keys to the end of the IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_AddRange">AddRange(IniKey[])</a></td><td>
Adds the specified keys to the end of the IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_Contains">Contains</a></td><td>
Determines whether the IniKeyCollection contains a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_Find">Find</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name, and returns the first occurrence within the entire IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_IndexOf">IndexOf</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name and returns the zero-based index of the first occurrence within the entire IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_Remove_1">Remove(String)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> from the IniKeyCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniKeyCollection_Remove">Remove(IniKey)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> from the IniKeyCollection.</td></tr></table>&nbsp;
<a href="#inikeycollection-class">Back to Top</a>

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
<a href="#inikeycollection-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />