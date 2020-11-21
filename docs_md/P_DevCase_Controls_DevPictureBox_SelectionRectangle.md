# DevPictureBox.SelectionRectangle Property 
 

Gets the selection rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public Rectangle SelectionRectangle { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public ReadOnly Property SelectionRectangle As Rectangle
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim value As Rectangle

value = instance.SelectionRectangle

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property Rectangle SelectionRectangle {
	Rectangle get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member SelectionRectangle : Rectangle with get

```


#### Property Value
Type: Rectangle<br />The selection rectangle.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />