# MruItem(*T*) Class
 

Represents a item of a most recent used List (MRU).


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Data.MruItem(T)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_Data_MruFileItem">DevCase.Core.Application.Data.MruFileItem</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("MruItem")]
public class MruItem<T> : AestheticObject

```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("MruItem")>
Public Class MruItem(Of T)
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As MruItem(Of T)
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"MruItem")]
generic<typename T>
public ref class MruItem : public AestheticObject
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("MruItem")>]
type MruItem<'T> =  
    class
        inherit AestheticObject
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "T:DevCase.Core.Application.Data.MruItem`1"\]</dd></dl>&nbsp;
The MruItem(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_MruItem_1__ctor">MruItem(T)</a></td><td>
Initializes a new instance of the MruItem(T) class.</td></tr></table>&nbsp;
<a href="#mruitem(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_MruItem_1_Date">Date</a></td><td>
Gets or sets the date on which this item was added to the MRU list.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_MruItem_1_Item">Item</a></td><td>
Gets the item.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_MruItem_1_Tag">Tag</a></td><td>
Gets or sets a tag for this MRU item. 

 A tag could contain any kind of additional info.</td></tr></table>&nbsp;
<a href="#mruitem(*t*)-class">Back to Top</a>

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
<a href="#mruitem(*t*)-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As New List(Of MruItem(Of String))

' Add some items into the collection.
With mruItems
    .Add(New MruItem(Of String)("Something1"))
    .Add(New MruItem(Of String)("Something1") With {.Date = Date.Now, .Tag = New Object()})
End With

' Serialize the MRU collection to file.
MruUtil.Save(mruItems, ".\MRU.tmp")

' Deserialize the MRU Item collection from file.
For Each mruItem As MruItem(Of String) In MruUtil.Load(Of IEnumerable(Of MruItem(Of String)))(".\MRU.tmp")
    MessageBox.Show(mruItem.FilePath)
Next mruItem

' Just another way to deserialize the collection:
MruUtil.Load(mruItems.ToList, ".\MRU.tmp")
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />