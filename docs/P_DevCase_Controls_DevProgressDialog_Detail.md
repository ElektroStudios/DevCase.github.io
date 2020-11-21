# DevProgressDialog.Detail Property 
 

Gets or sets the detail that appears on the second line.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string Detail { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property Detail As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As String

value = instance.Detail

instance.Detail = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ Detail {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member Detail : string with get, set

```


#### Property Value
Type: String<br />The detail.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />