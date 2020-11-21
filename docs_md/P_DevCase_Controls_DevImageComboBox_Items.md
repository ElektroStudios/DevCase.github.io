# DevImageComboBox.Items Property 
 

Gets a collection containing all items in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorAttribute(typeof(CollectionEditor), typeof(UITypeEditor))]
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
[DefaultValueAttribute(typeof(DevImageComboBoxItemCollection), "")]
public virtual DevImageComboBoxItemCollection Items { get; }
```

**VB**<br />
``` VB
<EditorAttribute(GetType(CollectionEditor), GetType(UITypeEditor))>
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
<DefaultValueAttribute(GetType(DevImageComboBoxItemCollection), "")>
Public Overridable ReadOnly Property Items As DevImageComboBoxItemCollection
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBox
Dim value As DevImageComboBoxItemCollection

value = instance.Items

```

**C++**<br />
``` C++
public:
[EditorAttribute(typeof(CollectionEditor), typeof(UITypeEditor))]
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
[DefaultValueAttribute(typeof(DevImageComboBoxItemCollection), L"")]
virtual property DevImageComboBoxItemCollection^ Items {
	DevImageComboBoxItemCollection^ get ();
}
```

**F#**<br />
``` F#
[<EditorAttribute(typeof(CollectionEditor), typeof(UITypeEditor))>]
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
[<DefaultValueAttribute(typeof(DevImageComboBoxItemCollection), "")>]
abstract Items : DevImageComboBoxItemCollection with get
[<EditorAttribute(typeof(CollectionEditor), typeof(UITypeEditor))>]
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
[<DefaultValueAttribute(typeof(DevImageComboBoxItemCollection), "")>]
override Items : DevImageComboBoxItemCollection with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevImageComboBoxData_DevImageComboBoxItemCollection">DevImageComboBoxItemCollection</a><br />A collection containing all items in the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevImageComboBox">DevImageComboBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />