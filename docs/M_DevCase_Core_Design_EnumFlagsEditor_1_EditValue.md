# EnumFlagsEditor(*TEnum*).EditValue Method 
 

Edits the specified object's value using the editor style indicated by the GetEditStyle() method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override Object EditValue(
	ITypeDescriptorContext context,
	IServiceProvider provider,
	Object value
)
```

**VB**<br />
``` VB
Public Overrides Function EditValue ( 
	context As ITypeDescriptorContext,
	provider As IServiceProvider,
	value As Object
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As EnumFlagsEditor
Dim context As ITypeDescriptorContext
Dim provider As IServiceProvider
Dim value As Object
Dim returnValue As Object

returnValue = instance.EditValue(context, 
	provider, value)
```

**C++**<br />
``` C++
public:
virtual Object^ EditValue(
	ITypeDescriptorContext^ context, 
	IServiceProvider^ provider, 
	Object^ value
) override
```

**F#**<br />
``` F#
abstract EditValue : 
        context : ITypeDescriptorContext * 
        provider : IServiceProvider * 
        value : Object -> Object 
override EditValue : 
        context : ITypeDescriptorContext * 
        provider : IServiceProvider * 
        value : Object -> Object 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that can be used to gain additional context information.</dd><dt>provider</dt><dd>Type: System.IServiceProvider<br />An IServiceProvider that this editor can use to obtain services.</dd><dt>value</dt><dd>Type: System.Object<br />The object to edit.</dd></dl>

#### Return Value
Type: Object<br />The new value of the object. 

 If the value of the object has not changed, this should return the same object it was passed.

## See Also


#### Reference
<a href="T_DevCase_Core_Design_EnumFlagsEditor_1">EnumFlagsEditor(TEnum) Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />