# OpenFileOrFolderDialog.Title Property 
 

Gets or sets the dialog box title.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string Title { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property Title As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim value As String

value = instance.Title

instance.Title = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ Title {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member Title : string with get, set

```


#### Property Value
Type: String<br />The dialog box title. The default value is an empty string ("").

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />