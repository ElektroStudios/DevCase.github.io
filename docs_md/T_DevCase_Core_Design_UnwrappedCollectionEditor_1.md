# UnwrappedCollectionEditor(*T*) Class
 

Provides a user interface that unwraps the items of a collection from the default "Value" property that is shown in a standard CollectionEditor. 

 Use UnwrappedCollectionEditor(T) if you want to show a collection whose items are types with properties that have category attributes (CategoryAttribute) applied.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Drawing.Design.UITypeEditor<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Design.CollectionEditor<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.UnwrappedCollectionEditor(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class UnwrappedCollectionEditor<T> : CollectionEditor

```

**VB**<br />
``` VB
Public NotInheritable Class UnwrappedCollectionEditor(Of T)
	Inherits CollectionEditor
```

**VB Usage**<br />
``` VB Usage
Dim instance As UnwrappedCollectionEditor(Of T)
```

**C++**<br />
``` C++
generic<typename T>
public ref class UnwrappedCollectionEditor sealed : public CollectionEditor
```

**F#**<br />
``` F#
[<SealedAttribute>]
type UnwrappedCollectionEditor<'T> =  
    class
        inherit CollectionEditor
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>&nbsp;
The UnwrappedCollectionEditor(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_UnwrappedCollectionEditor_1__ctor">UnwrappedCollectionEditor(T)</a></td><td>
Initializes a new instance of the UnwrappedCollectionEditor(T) class.</td></tr></table>&nbsp;
<a href="#unwrappedcollectioneditor(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_UnwrappedCollectionEditor_1_EditValue">EditValue</a></td><td>
Edits the value of the specified object using the specified service provider and context.
 (Overrides CollectionEditor.EditValue(ITypeDescriptorContext, IServiceProvider, Object).)</td></tr></table>&nbsp;
<a href="#unwrappedcollectioneditor(*t*)-class">Back to Top</a>

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
<a href="#unwrappedcollectioneditor(*t*)-class">Back to Top</a>

## Remarks
Credits for Reza Aghaei's code: <a href="https://stackoverflow.com/a/53890224/1248295" target="_blank">https://stackoverflow.com/a/53890224/1248295</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class TestClass

    <Editor(GetType(UnwrappedCollectionEditor(Of TestItem)), GetType(UITypeEditor))>
    <TypeConverter(GetType(CollectionEditor))>
    Public ReadOnly Property TestCollection As ReadOnlyCollection(Of TestItem)
        Get
            Dim collection As New List(Of TestItem)
            For i As Integer = 0 To 10
                collection.Add(New TestItem())
            Next
            Return collection.AsReadOnly()
        End Get
    End Property

    Public Sub New()
    End Sub

End Class

Public NotInheritable Class TestItem

    <Category("Category 1")>
    Public ReadOnly Property TestProperty1 As String = "Test"

    <Category("Category 2")>
    Public ReadOnly Property TestProperty2 As String = "Test"

    <Category("Category 3")>
    Public ReadOnly Property TestProperty3 As String = "Test"

    Public Sub New()
    End Sub

End Class

' Then, in another part of your source-code you will show the collection in a PropertyGrid control...:

Dim obj As New TestClass()
Me.PropertyGrid1.SelectedObject = obj
```


## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />