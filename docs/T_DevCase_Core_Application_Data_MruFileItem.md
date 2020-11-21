# MruFileItem Class
 

Represents a File-item of a most recent used List (MRU).


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_Data_MruItem_1">DevCase.Core.Application.Data.MruItem</a>(FileInfo)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Data.MruFileItem<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("MruFileItem")]
public class MruFileItem : MruItem<FileInfo>
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("MruFileItem")>
Public Class MruFileItem
	Inherits MruItem(Of FileInfo)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MruFileItem
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"MruFileItem")]
public ref class MruFileItem : public MruItem<FileInfo^>
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("MruFileItem")>]
type MruFileItem =  
    class
        inherit MruItem<FileInfo>
    end
```

The MruFileItem type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_MruFileItem__ctor">MruFileItem</a></td><td>
Initializes a new instance of the MruFileItem class.</td></tr></table>&nbsp;
<a href="#mrufileitem-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_MruFileItem_FilePath">FilePath</a></td><td>
Gets the item filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_MruFileItem_Icon">Icon</a></td><td>
Gets or sets the file icon.</td></tr></table>&nbsp;
<a href="#mrufileitem-class">Back to Top</a>

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
<a href="#mrufileitem-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As New List(Of MruFileItem)

' Add some items into the collection.
With mruItems
    .Add(New MruFileItem("C:\File1.ext"))
    .Add(New MruFileItem("C:\File2.ext") With {.Date = Date.Now,
                                               .Icon = Bitmap.FromFile("C:\Icon.ico"),
                                               .Tag = New Object()})
End With

' Serialize the MRU collection to file.
MruUtil.Save(mruItems, ".\MRU.tmp")

' Deserialize the MRU Item collection from file.
For Each mruItem As MruFileItem In MruUtil.Load(Of IEnumerable(Of MruFileItem))(".\MRU.tmp")
    MessageBox.Show(mruItem.FilePath)
Next mruItem

' Just another way to deserialize the collection:
MruUtil.Load(mruItems.ToList, ".\MRU.tmp")
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />