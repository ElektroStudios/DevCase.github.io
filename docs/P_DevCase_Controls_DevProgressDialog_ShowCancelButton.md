# DevProgressDialog.ShowCancelButton Property 
 

Gets or sets a value indicating whether a Cancel button is displayed on the progress dialog.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(true)]
public bool ShowCancelButton { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(true)>
Public Property ShowCancelButton As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As Boolean

value = instance.ShowCancelButton

instance.ShowCancelButton = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(true)]
property bool ShowCancelButton {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(true)>]
member ShowCancelButton : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) to display a Cancel button on the progress dialog; otherwise, `false` (`False` in Visual Basic). 

 The default is `true` (`True` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />