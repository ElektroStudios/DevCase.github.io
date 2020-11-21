# FileSizeConverter Class
 

Provides a type converter to converts a numeric value into a string that represents the number expressed as a size value in bytes, kilobytes, megabytes, gigabytes, petabytes or exabytes, depending on the size. 

 Conversion examples: 

 Input value -> Result string 

 793 -> 793 Bytes 

 1533 -> 1,49 KB 

 2049 -> 2,00 KB


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.ComponentModel.TypeConverter<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.FileSizeConverter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class FileSizeConverter : TypeConverter
```

**VB**<br />
``` VB
Public Class FileSizeConverter
	Inherits TypeConverter
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSizeConverter
```

**C++**<br />
``` C++
public ref class FileSizeConverter : public TypeConverter
```

**F#**<br />
``` F#
type FileSizeConverter =  
    class
        inherit TypeConverter
    end
```

The FileSizeConverter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_FileSizeConverter__ctor">FileSizeConverter</a></td><td>
Initializes a new instance of the FileSizeConverter class.</td></tr></table>&nbsp;
<a href="#filesizeconverter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_FileSizeConverter_CanConvertFrom">CanConvertFrom</a></td><td>
Determines if this converter can convert an object in the given source type to the native type of the converter.
 (Overrides TypeConverter.CanConvertFrom(ITypeDescriptorContext, Type).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_FileSizeConverter_CanConvertTo">CanConvertTo</a></td><td>
Returns whether this converter can convert the object to the specified type, using the specified context.
 (Overrides TypeConverter.CanConvertTo(ITypeDescriptorContext, Type).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_FileSizeConverter_ConvertTo">ConvertTo</a></td><td>
Converts the specified object to another type.
 (Overrides TypeConverter.ConvertTo(ITypeDescriptorContext, CultureInfo, Object, Type).)</td></tr></table>&nbsp;
<a href="#filesizeconverter-class">Back to Top</a>

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
<a href="#filesizeconverter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load
        Me.PropertyGrid1.SelectedObject = New TestClass
    End Sub

End Class

Public Class TestClass

    <TypeConverter(GetType(FileSizeConverter))>
    Public ReadOnly Property FileSize1 As Long = 1024 ' Bytes

    <TypeConverter(GetType(FileSizeConverter))>
    Public ReadOnly Property FileSize2 As New Filesize(1024, SizeUnits.Byte)

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />