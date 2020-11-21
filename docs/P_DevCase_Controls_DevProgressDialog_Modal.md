# DevProgressDialog.Modal Property 
 

Gets a value indicating whether this form is displayed modally.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool Modal { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property Modal As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As Boolean

value = instance.Modal

instance.Modal = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool Modal {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member Modal : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the form is displayed modally; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />