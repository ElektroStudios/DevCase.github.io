# DevProgressDialog.HideTimeRemaining Property 
 

Gets or sets a value indicating whether to show the "time remaining" text.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool HideTimeRemaining { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property HideTimeRemaining As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As Boolean

value = instance.HideTimeRemaining

instance.HideTimeRemaining = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool HideTimeRemaining {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member HideTimeRemaining : bool with get, set

```


#### Property Value
Type: Boolean<br />Show the "time remaining" text.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />