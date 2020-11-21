# PercentageTypeConverter.CanConvertFrom Method 
 

Returns whether this converter can convert an object of the given type to the type of this converter, using the specified context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override bool CanConvertFrom(
	ITypeDescriptorContext context,
	Type sourceType
)
```

**VB**<br />
``` VB
Public Overrides Function CanConvertFrom ( 
	context As ITypeDescriptorContext,
	sourceType As Type
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As PercentageTypeConverter
Dim context As ITypeDescriptorContext
Dim sourceType As Type
Dim returnValue As Boolean

returnValue = instance.CanConvertFrom(context, 
	sourceType)
```

**C++**<br />
``` C++
public:
virtual bool CanConvertFrom(
	ITypeDescriptorContext^ context, 
	Type^ sourceType
) override
```

**F#**<br />
``` F#
abstract CanConvertFrom : 
        context : ITypeDescriptorContext * 
        sourceType : Type -> bool 
override CanConvertFrom : 
        context : ITypeDescriptorContext * 
        sourceType : Type -> bool 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that provides a format context.</dd><dt>sourceType</dt><dd>Type: System.Type<br />A Type that represents the type you want to convert from.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if this converter can perform the conversion; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Design_PercentageTypeConverter">PercentageTypeConverter Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />