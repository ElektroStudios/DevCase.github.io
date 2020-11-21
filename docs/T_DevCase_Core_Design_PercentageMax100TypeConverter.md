# PercentageMax100TypeConverter Class
 

Provides a unified way of converting types of values to a percentage value in range of 0% to 100%.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.ComponentModel.TypeConverter<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_PercentageTypeConverter">DevCase.Core.Design.PercentageTypeConverter</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.PercentageMax100TypeConverter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class PercentageMax100TypeConverter : PercentageTypeConverter
```

**VB**<br />
``` VB
Public Class PercentageMax100TypeConverter
	Inherits PercentageTypeConverter
```

**VB Usage**<br />
``` VB Usage
Dim instance As PercentageMax100TypeConverter
```

**C++**<br />
``` C++
public ref class PercentageMax100TypeConverter : public PercentageTypeConverter
```

**F#**<br />
``` F#
type PercentageMax100TypeConverter =  
    class
        inherit PercentageTypeConverter
    end
```

The PercentageMax100TypeConverter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_PercentageMax100TypeConverter__ctor">PercentageMax100TypeConverter</a></td><td>
Initializes a new instance of the PercentageMax100TypeConverter class.</td></tr></table>&nbsp;
<a href="#percentagemax100typeconverter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_PercentageMax100TypeConverter_ConvertFrom">ConvertFrom</a></td><td>
Converts the given object to the type of this converter, using the specified context and culture information.
 (Overrides <a href="M_DevCase_Core_Design_PercentageTypeConverter_ConvertFrom">PercentageTypeConverter.ConvertFrom(ITypeDescriptorContext, CultureInfo, Object)</a>.)</td></tr></table>&nbsp;
<a href="#percentagemax100typeconverter-class">Back to Top</a>

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
<a href="#percentagemax100typeconverter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
<TypeConverter(GetType(PercentageMax100TypeConverter))>
<DefaultValue(GetType(Double), "1.0")>
<Browsable(True)>
Public Property Opacity As Double
    Get
        Return Me.opacityB
    End Get
    Set(ByVal value As Double)
        If (value < 0.0R) Then ' Avoid negative values.
            value = 0.0R
        End If
        If (value > 1.0R) Then ' Avoid values above maximum opacity.
            value = 1.0R
        End If
        Me.opacityB = value
    End Set
End Property

Private opacityB As Double = 1.0R ' Default opacity: x1.0 ( translated as string: 100% )
```


## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />System.ComponentModel.TypeConverter<br />