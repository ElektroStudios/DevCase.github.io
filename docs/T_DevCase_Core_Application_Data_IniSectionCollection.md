# IniSectionCollection Class
 

Represents a strongly typed list of <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that can be accessed by an index.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.ObjectModel.Collection(<a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a>)<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticCollection_1">DevCase.Core.Design.AestheticCollection</a>(<a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a>)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Data.IniSectionCollection<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("IniSectionCollection")]
public sealed class IniSectionCollection : AestheticCollection<IniSection>
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("IniSectionCollection")>
Public NotInheritable Class IniSectionCollection
	Inherits AestheticCollection(Of IniSection)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"IniSectionCollection")]
public ref class IniSectionCollection sealed : public AestheticCollection<IniSection^>
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("IniSectionCollection")>]
type IniSectionCollection =  
    class
        inherit AestheticCollection<IniSection>
    end
```

The IniSectionCollection type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection__ctor">IniSectionCollection</a></td><td>
Initializes a new instance of the IniSectionCollection class.</td></tr></table>&nbsp;
<a href="#inisectioncollection-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_IniSectionCollection_Item">Item</a></td><td>
Gets or sets the <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name.</td></tr></table>&nbsp;
<a href="#inisectioncollection-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_Add_1">Add(String)</a></td><td>
Adds a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> to the end of the IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_Add">Add(IniSection)</a></td><td>
Adds a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> to the end of the IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_AddRange_1">AddRange(String[])</a></td><td>
Adds the specified section names to the end of the IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_AddRange">AddRange(IniSection[])</a></td><td>
Adds the specified sections to the end of the IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_Contains">Contains</a></td><td>
Determines whether the IniSectionCollection contains a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_Find">Find</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name, and returns the first occurrence within the entire IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_IndexOf">IndexOf</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name and returns the zero-based index of the first occurrence within the entire IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_Remove_1">Remove(String)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> from the IniSectionCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_IniSectionCollection_Remove">Remove(IniSection)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> from the IniSectionCollection.</td></tr></table>&nbsp;
<a href="#inisectioncollection-class">Back to Top</a>

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
<a href="#inisectioncollection-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />