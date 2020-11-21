# ShortcutFileInfo.WorkingDirectory Property 
 

Gets or sets the working directory of the target file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
[EditorAttribute(typeof(FolderNameEditor), typeof(UITypeEditor))]
public string WorkingDirectory { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
<EditorAttribute(GetType(FolderNameEditor), GetType(UITypeEditor))>
Public Property WorkingDirectory As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim value As String

value = instance.WorkingDirectory

instance.WorkingDirectory = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
[EditorAttribute(typeof(FolderNameEditor), typeof(UITypeEditor))]
property String^ WorkingDirectory {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
[<EditorAttribute(typeof(FolderNameEditor), typeof(UITypeEditor))>]
member WorkingDirectory : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.IO.ShortcutFileInfo.WorkingDirectory"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />