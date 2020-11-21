# DevImageComboBoxItemCollection Class
 

Represents the collection of items in a <a href="T_DevCase_Controls_DevImageComboBox">DevImageComboBox</a> control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Windows.Forms.ComboBox.ObjectCollection<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevImageComboBoxData.DevImageComboBoxItemCollection<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ListBindableAttribute(false)]
public sealed class DevImageComboBoxItemCollection : ComboBox.ObjectCollection
```

**VB**<br />
``` VB
<ListBindableAttribute(false)>
Public NotInheritable Class DevImageComboBoxItemCollection
	Inherits ComboBox.ObjectCollection
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBoxItemCollection
```

**C++**<br />
``` C++
[ListBindableAttribute(false)]
public ref class DevImageComboBoxItemCollection sealed : public ComboBox.ObjectCollection
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ListBindableAttribute(false)>]
type DevImageComboBoxItemCollection =  
    class
        inherit ComboBox.ObjectCollection
    end
```

The DevImageComboBoxItemCollection type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection__ctor">DevImageComboBoxItemCollection</a></td><td>
Initializes a new instance of the DevImageComboBoxItemCollection class.</td></tr></table>&nbsp;
<a href="#devimagecomboboxitemcollection-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Add">Add</a></td><td>
Adds the specified item to the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_AddRange">AddRange</a></td><td>
Adds an array of items to the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Contains">Contains(DevImageComboBoxItem)</a></td><td>
Determines whether the specified item is located within the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Contains_1">Contains(String)</a></td><td>
Determines whether the specified item is located within the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_IndexOf">IndexOf(DevImageComboBoxItem)</a></td><td>
Retrieves the index within the collection of the specified item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_IndexOf_1">IndexOf(String)</a></td><td>
Retrieves the index within the collection of the specified item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Insert">Insert</a></td><td>
Inserts an item into the collection at the specified index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Remove">Remove(DevImageComboBoxItem)</a></td><td>
Removes the specified item from the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection_Remove_1">Remove(String)</a></td><td>
Removes the specified item from the collection.</td></tr></table>&nbsp;
<a href="#devimagecomboboxitemcollection-class">Back to Top</a>

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
<a href="#devimagecomboboxitemcollection-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls_DevImageComboBoxData">DevCase.Controls.DevImageComboBoxData Namespace</a><br />System.Windows.Forms.ComboBox.ObjectCollection<br />