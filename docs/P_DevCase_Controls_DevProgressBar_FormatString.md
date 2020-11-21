# DevProgressBar.FormatString Property 
 

Gets or sets the percentage format string that will be displayed on the control when its current state is <a href="T_DevCase_Controls_DevProgressBarData_DevProgressBarState">Normal</a>. 

 #current=Current Value #total=Maximum Value #%=Current Percentage

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(string), "(#current / #total) #%")]
public virtual string FormatString { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(String), "(#current / #total) #%")>
Public Overridable Property FormatString As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressBar
Dim value As String

value = instance.FormatString

instance.FormatString = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(String), L"(#current / #total) #%")]
virtual property String^ FormatString {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(string), "(#current / #total) #%")>]
abstract FormatString : string with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(string), "(#current / #total) #%")>]
override FormatString : string with get, set
```


#### Property Value
Type: String<br />The percentage format string that will be displayed in the control when its current state is <a href="T_DevCase_Controls_DevProgressBarData_DevProgressBarState">Normal</a>.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressBar">DevProgressBar Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />