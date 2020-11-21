# EncodingTypeConverter.ConvertFrom Method 
 

Converts the given object to the type of this converter, using the specified context and culture information.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override Object ConvertFrom(
	ITypeDescriptorContext context,
	CultureInfo culture,
	Object value
)
```

**VB**<br />
``` VB
Public Overrides Function ConvertFrom ( 
	context As ITypeDescriptorContext,
	culture As CultureInfo,
	value As Object
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As EncodingTypeConverter
Dim context As ITypeDescriptorContext
Dim culture As CultureInfo
Dim value As Object
Dim returnValue As Object

returnValue = instance.ConvertFrom(context, 
	culture, value)
```

**C++**<br />
``` C++
public:
virtual Object^ ConvertFrom(
	ITypeDescriptorContext^ context, 
	CultureInfo^ culture, 
	Object^ value
) override
```

**F#**<br />
``` F#
abstract ConvertFrom : 
        context : ITypeDescriptorContext * 
        culture : CultureInfo * 
        value : Object -> Object 
override ConvertFrom : 
        context : ITypeDescriptorContext * 
        culture : CultureInfo * 
        value : Object -> Object 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that provides a format context.</dd><dt>culture</dt><dd>Type: System.Globalization.CultureInfo<br />The CultureInfo to use as the current culture.</dd><dt>value</dt><dd>Type: System.Object<br />The Object to convert.</dd></dl>

#### Return Value
Type: Object<br />An Object that represents the converted value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FormatException</td><td>Valid Range is between 0% and 100%.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Design_EncodingTypeConverter">EncodingTypeConverter Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />