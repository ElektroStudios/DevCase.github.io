# EncodingTypeConverter.ConvertTo Method 
 

Converts the given value object to the specified type, using the specified context and culture information.

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
Dim instance As EncodingTypeConverter
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
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that provides a format context.</dd><dt>culture</dt><dd>Type: System.Globalization.CultureInfo<br />A CultureInfo. If null is passed, the current culture is assumed.</dd><dt>value</dt><dd>Type: System.Object<br />The Object to convert.</dd><dt>destinationType</dt><dd>Type: System.Type<br />The Type to convert the *value* parameter to.</dd></dl>

#### Return Value
Type: Object<br />An Object that represents the converted value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>destinationType</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Design_EncodingTypeConverter">EncodingTypeConverter Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />