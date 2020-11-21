# DevProgressDialog.Description Property 
 

Gets or sets the description that appears on the first line.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string Description { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property Description As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As String

value = instance.Description

instance.Description = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ Description {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member Description : string with get, set

```


#### Property Value
Type: String<br />The description.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />