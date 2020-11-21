# EncodingTypeConverter Class
 

Provides a unified way of converting types of values to a Encoding object.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.ComponentModel.TypeConverter<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.EncodingTypeConverter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class EncodingTypeConverter : TypeConverter
```

**VB**<br />
``` VB
Public Class EncodingTypeConverter
	Inherits TypeConverter
```

**VB Usage**<br />
``` VB Usage
Dim instance As EncodingTypeConverter
```

**C++**<br />
``` C++
public ref class EncodingTypeConverter : public TypeConverter
```

**F#**<br />
``` F#
type EncodingTypeConverter =  
    class
        inherit TypeConverter
    end
```

The EncodingTypeConverter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EncodingTypeConverter__ctor">EncodingTypeConverter</a></td><td>
Initializes a new instance of the EncodingTypeConverter class.</td></tr></table>&nbsp;
<a href="#encodingtypeconverter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EncodingTypeConverter_CanConvertFrom">CanConvertFrom</a></td><td>
Returns whether this converter can convert an object of the given type to the type of this converter, using the specified context.
 (Overrides TypeConverter.CanConvertFrom(ITypeDescriptorContext, Type).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EncodingTypeConverter_CanConvertTo">CanConvertTo</a></td><td>
Returns whether this converter can convert the object to the specified type, using the specified context.
 (Overrides TypeConverter.CanConvertTo(ITypeDescriptorContext, Type).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EncodingTypeConverter_ConvertFrom">ConvertFrom</a></td><td>
Converts the given object to the type of this converter, using the specified context and culture information.
 (Overrides TypeConverter.ConvertFrom(ITypeDescriptorContext, CultureInfo, Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EncodingTypeConverter_ConvertTo">ConvertTo</a></td><td>
Converts the given value object to the specified type, using the specified context and culture information.
 (Overrides TypeConverter.ConvertTo(ITypeDescriptorContext, CultureInfo, Object, Type).)</td></tr></table>&nbsp;
<a href="#encodingtypeconverter-class">Back to Top</a>

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
<a href="#encodingtypeconverter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
<TypeConverter(GetType(EncodingTypeConverter))>
<DefaultValue(GetType(String), "UTF-8")>
<Browsable(True)>
Public Property TextEncoding As Encoding = Encoding.UTF8

<TypeConverter(GetType(EncodingTypeConverter))>
<DefaultValue(GetType(String), "UTF-8")>
<Browsable(True)>
Public Property TextEncodingName As String = "UTF-8"
```


## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />System.ComponentModel.TypeConverter<br />