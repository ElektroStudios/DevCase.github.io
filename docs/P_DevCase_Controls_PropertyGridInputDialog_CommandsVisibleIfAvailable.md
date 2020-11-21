# PropertyGridInputDialog.CommandsVisibleIfAvailable Property 
 

Gets or sets a value indicating whether the commands pane is visible for objects that expose verbs.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(true)]
public bool CommandsVisibleIfAvailable { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(true)>
Public Property CommandsVisibleIfAvailable As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim value As Boolean

value = instance.CommandsVisibleIfAvailable

instance.CommandsVisibleIfAvailable = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(true)]
property bool CommandsVisibleIfAvailable {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(true)>]
member CommandsVisibleIfAvailable : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the commands pane is visible; otherwise, `false` (`False` in Visual Basic). The default is `true` (`True` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />