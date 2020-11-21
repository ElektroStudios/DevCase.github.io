# FileOrFolderNameEditor.GetEditStyle Method 
 

Gets the editor style used by the EditValue(IServiceProvider, Object) method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override UITypeEditorEditStyle GetEditStyle(
	ITypeDescriptorContext context
)
```

**VB**<br />
``` VB
Public Overrides Function GetEditStyle ( 
	context As ITypeDescriptorContext
) As UITypeEditorEditStyle
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileOrFolderNameEditor
Dim context As ITypeDescriptorContext
Dim returnValue As UITypeEditorEditStyle

returnValue = instance.GetEditStyle(context)
```

**C++**<br />
``` C++
public:
virtual UITypeEditorEditStyle GetEditStyle(
	ITypeDescriptorContext^ context
) override
```

**F#**<br />
``` F#
abstract GetEditStyle : 
        context : ITypeDescriptorContext -> UITypeEditorEditStyle 
override GetEditStyle : 
        context : ITypeDescriptorContext -> UITypeEditorEditStyle 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: System.ComponentModel.ITypeDescriptorContext<br />An ITypeDescriptorContext that can be used to gain additional context information.</dd></dl>

#### Return Value
Type: UITypeEditorEditStyle<br />A UITypeEditorEditStyle value that indicates the style of editor used by the EditValue(IServiceProvider, Object) method. 

 If the UITypeEditor does not support this method, then GetEditStyle() will return None.

## See Also


#### Reference
<a href="T_DevCase_Core_Design_FileOrFolderNameEditor">FileOrFolderNameEditor Class</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />