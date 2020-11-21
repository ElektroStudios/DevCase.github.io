# AestheticList(*T*) Class
 

This is a class to consume for aesthetic purposes. 

 A default (emptyness) class that inherits from List(T), with these base members hidden: 

GetHashCode(), GetType(), Equals(Object), Equals(Object, Object), ReferenceEquals(Object, Object), ToString().


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.Generic.List(*T*)<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticList(T)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Text_TexfileLines">DevCase.Core.Text.TexfileLines</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public abstract class AestheticList<T> : List<T>

```

**VB**<br />
``` VB
Public MustInherit Class AestheticList(Of T)
	Inherits List(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim instance As AestheticList(Of T)
```

**C++**<br />
``` C++
generic<typename T>
public ref class AestheticList abstract : public List<T>
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
type AestheticList<'T> =  
    class
        inherit List<'T>
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "T:DevCase.Core.Design.AestheticList`1"\]</dd></dl>&nbsp;
The AestheticList(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticList_1__ctor">AestheticList(T)()</a></td><td>
Initializes a new instance of the AestheticList(T) class is empty and has the default initial capacity.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticList_1__ctor_1">AestheticList(T)(IEnumerable(T))</a></td><td>
Initializes a new instance of the AestheticList(T) class that contains elements copied from the specified collection and has sufficient capacity to accommodate the number of elements copied.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticList_1__ctor_2">AestheticList(T)(Int32)</a></td><td>
Initializes a new instance of the AestheticList(T) class is empty and has the specified initial capacity.</td></tr></table>&nbsp;
<a href="#aestheticlist(*t*)-class">Back to Top</a>

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
<a href="#aestheticlist(*t*)-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />