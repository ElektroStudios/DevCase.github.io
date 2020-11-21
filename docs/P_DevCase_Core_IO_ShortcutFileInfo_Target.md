# ShortcutFileInfo.Target Property 
 

Gets or sets the full path of the target file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
[EditorAttribute(typeof(FileOrFolderNameEditor), typeof(UITypeEditor))]
public string Target { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
<EditorAttribute(GetType(FileOrFolderNameEditor), GetType(UITypeEditor))>
Public Property Target As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim value As String

value = instance.Target

instance.Target = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
[EditorAttribute(typeof(FileOrFolderNameEditor), typeof(UITypeEditor))]
property String^ Target {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
[<EditorAttribute(typeof(FileOrFolderNameEditor), typeof(UITypeEditor))>]
member Target : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.IO.ShortcutFileInfo.Target"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />