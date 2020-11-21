# FileSizeConverter.CanConvertTo Method 
 

Returns whether this converter can convert the object to the specified type, using the specified context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override bool CanConvertTo(
	ITypeDescriptorContext context,
	Type destinationType
)
```

**VB**<br />
``` VB
Public Overrides Function CanConvertTo ( 
	context As ITypeDescriptorContext,
	destinationType As Type
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSizeConverter
Dim context As ITypeDescriptorContext
Dim destinationType As Type
Dim returnValue As Boolean

returnValue = instance.CanConvertTo(context, 
	destinationType)
```

**C++**<br />
``` C++
public:
virtual bool CanConvertTo(
	ITypeDescriptorContext^ context, 
	Type^ destinationType
) override
```

**F#**<br />
``` F#
abstract CanConvertTo : 
        context : ITypeDescriptorContext * 
        destinationType : Type -> bool 
override CanConvertTo : 
        context : ITypeDescriptorContext * 
        destinationType : Type -> bool 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that provides a format context.</dd><dt>destinationType</dt><dd>Type: System.Type<br />A Type that represents the type you want to convert to.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if this converter can perform the conversion; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Design_FileSizeConverter">FileSizeConverter Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />