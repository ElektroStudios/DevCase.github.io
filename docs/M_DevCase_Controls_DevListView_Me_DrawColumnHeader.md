# DevListView.Me_DrawColumnHeader Method 
 

Handles the DrawColumnHeader event of the Me control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Me_DrawColumnHeader(
	Object sender,
	DrawListViewColumnHeaderEventArgs e
)
```

**VB**<br />
``` VB
Public Sub Me_DrawColumnHeader ( 
	sender As Object,
	e As DrawListViewColumnHeaderEventArgs
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListView
Dim sender As Object
Dim e As DrawListViewColumnHeaderEventArgs

instance.Me_DrawColumnHeader(sender, 
	e)
```

**C++**<br />
``` C++
public:
void Me_DrawColumnHeader(
	Object^ sender, 
	DrawListViewColumnHeaderEventArgs^ e
)
```

**F#**<br />
``` F#
member Me_DrawColumnHeader : 
        sender : Object * 
        e : DrawListViewColumnHeaderEventArgs -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br />The source of the event.</dd><dt>e</dt><dd>Type: System.Windows.Forms.DrawListViewColumnHeaderEventArgs<br />The DrawListViewColumnHeaderEventArgs instance containing the event data.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListView">DevListView Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />