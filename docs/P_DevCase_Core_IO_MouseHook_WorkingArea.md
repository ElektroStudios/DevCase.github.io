# MouseHook.WorkingArea Property 
 

Gets or sets the screen's working area on which to notify about mouse events. 

 The events fired by this mouseHook will be restricted to the bounds of the specified rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Rectangle WorkingArea { get; set; }
```

**VB**<br />
``` VB
Public Property WorkingArea As Rectangle
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseHook
Dim value As Rectangle

value = instance.WorkingArea

instance.WorkingArea = value
```

**C++**<br />
``` C++
public:
property Rectangle WorkingArea {
	Rectangle get ();
	void set (Rectangle value);
}
```

**F#**<br />
``` F#
member WorkingArea : Rectangle with get, set

```


#### Property Value
Type: Rectangle<br />The screen's working area on which to notify about mouse events.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseHook">MouseHook Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />