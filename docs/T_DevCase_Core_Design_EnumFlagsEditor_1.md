# EnumFlagsEditor(*TEnum*) Class
 

Provides a user interface for selecting the values of a Enum with or without the FlagsAttribute attribute class specified. 




## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Drawing.Design.UITypeEditor<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.EnumFlagsEditor(TEnum)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class EnumFlagsEditor<TEnum> : UITypeEditor
where TEnum : struct, new()

```

**VB**<br />
``` VB
Public Class EnumFlagsEditor(Of TEnum As {Structure, New})
	Inherits UITypeEditor
```

**VB Usage**<br />
``` VB Usage
Dim instance As EnumFlagsEditor(Of TEnum)
```

**C++**<br />
``` C++
generic<typename TEnum>
where TEnum : value class, gcnew()
public ref class EnumFlagsEditor : public UITypeEditor
```

**F#**<br />
``` F#
type EnumFlagsEditor<'TEnum when 'TEnum : struct, new()> =  
    class
        inherit UITypeEditor
    end
```


#### Type Parameters
&nbsp;<dl><dt>TEnum</dt><dd>The type of the Enum.</dd></dl>&nbsp;
The EnumFlagsEditor(TEnum) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EnumFlagsEditor_1__ctor">EnumFlagsEditor(TEnum)</a></td><td>
Initializes a new instance of the EnumFlagsEditor(TEnum) class.</td></tr></table>&nbsp;
<a href="#enumflagseditor(*tenum*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EnumFlagsEditor_1_EditValue">EditValue</a></td><td>
Edits the specified object's value using the editor style indicated by the GetEditStyle() method.
 (Overrides UITypeEditor.EditValue(ITypeDescriptorContext, IServiceProvider, Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_EnumFlagsEditor_1_GetEditStyle">GetEditStyle</a></td><td>
Gets the editor style used by the EditValue(IServiceProvider, Object) method.
 (Overrides UITypeEditor.GetEditStyle(ITypeDescriptorContext).)</td></tr></table>&nbsp;
<a href="#enumflagseditor(*tenum*)-class">Back to Top</a>

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
<a href="#enumflagseditor(*tenum*)-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />System.Drawing.Design.UITypeEditor<br />