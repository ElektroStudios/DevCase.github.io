# FileSizeConverter.ConvertTo Method 
 

Converts the specified object to another type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override Object ConvertTo(
	ITypeDescriptorContext context,
	CultureInfo culture,
	Object value,
	Type destinationType
)
```

**VB**<br />
``` VB
Public Overrides Function ConvertTo ( 
	context As ITypeDescriptorContext,
	culture As CultureInfo,
	value As Object,
	destinationType As Type
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSizeConverter
Dim context As ITypeDescriptorContext
Dim culture As CultureInfo
Dim value As Object
Dim destinationType As Type
Dim returnValue As Object

returnValue = instance.ConvertTo(context, 
	culture, value, destinationType)
```

**C++**<br />
``` C++
public:
virtual Object^ ConvertTo(
	ITypeDescriptorContext^ context, 
	CultureInfo^ culture, 
	Object^ value, 
	Type^ destinationType
) override
```

**F#**<br />
``` F#
abstract ConvertTo : 
        context : ITypeDescriptorContext * 
        culture : CultureInfo * 
        value : Object * 
        destinationType : Type -> Object 
override ConvertTo : 
        context : ITypeDescriptorContext * 
        culture : CultureInfo * 
        value : Object * 
        destinationType : Type -> Object 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that provides a format context.</dd><dt>culture</dt><dd>Type: System.Globalization.CultureInfo<br />A CultureInfo that specifies the culture to represent the number.</dd><dt>value</dt><dd>Type: System.Object<br />The object to convert.</dd><dt>destinationType</dt><dd>Type: System.Type<br />The type to convert the object to.</dd></dl>

#### Return Value
Type: Object<br />An Object that represents the converted value.

## See Also


#### Reference
<a href="T_DevCase_Core_Design_FileSizeConverter">FileSizeConverter Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />