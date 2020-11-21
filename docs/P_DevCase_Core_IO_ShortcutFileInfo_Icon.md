# ShortcutFileInfo.Icon Property 
 

Gets or sets the full path of the icon file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
[EditorAttribute(typeof(IconFileNameEditor), typeof(UITypeEditor))]
public string Icon { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
<EditorAttribute(GetType(IconFileNameEditor), GetType(UITypeEditor))>
Public Property Icon As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim value As String

value = instance.Icon

instance.Icon = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
[EditorAttribute(typeof(IconFileNameEditor), typeof(UITypeEditor))]
property String^ Icon {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
[<EditorAttribute(typeof(IconFileNameEditor), typeof(UITypeEditor))>]
member Icon : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.IO.ShortcutFileInfo.Icon"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />