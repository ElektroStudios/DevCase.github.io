# UnwrappedCollectionEditor(*T*).EditValue Method 
 

Edits the value of the specified object using the specified service provider and context.

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
Dim instance As UnwrappedCollectionEditor
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
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that can be used to gain additional context information.</dd><dt>provider</dt><dd>Type: System.IServiceProvider<br />A service provider object through which editing services can be obtained.</dd><dt>value</dt><dd>Type: System.Object<br />The object to edit the value of.</dd></dl>

#### Return Value
Type: Object<br />The new value of the object. If the value of the object has not changed, this should return the same object it was passed.

## See Also


#### Reference
<a href="T_DevCase_Core_Design_UnwrappedCollectionEditor_1">UnwrappedCollectionEditor(T) Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />