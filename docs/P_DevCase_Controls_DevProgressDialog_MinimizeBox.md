# DevProgressDialog.MinimizeBox Property 
 

Gets or sets a value indicating whether the Minimize button is displayed in the caption bar of the progress dialog.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(true)]
public bool MinimizeBox { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(true)>
Public Property MinimizeBox As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim value As Boolean

value = instance.MinimizeBox

instance.MinimizeBox = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(true)]
property bool MinimizeBox {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(true)>]
member MinimizeBox : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) to display a Minimize button for the dialog; otherwise, `false` (`False` in Visual Basic). 

 The default is `true` (`True` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />