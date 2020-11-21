# OpenFileOrFolderDialog.InitialDirectory Property 
 

Gets or sets the initial directory displayed by the dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string InitialDirectory { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property InitialDirectory As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim value As String

value = instance.InitialDirectory

instance.InitialDirectory = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ InitialDirectory {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member InitialDirectory : string with get, set

```


#### Property Value
Type: String<br />The initial directory displayed by the dialog box. The default is an empty string ("").

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />