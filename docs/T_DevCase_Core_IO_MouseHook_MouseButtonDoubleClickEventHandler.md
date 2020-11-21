# MouseHook.MouseButtonDoubleClickEventHandler Delegate
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate void MouseButtonDoubleClickEventHandler(
	Object sender,
	Point mouseLocation,
	MouseButton mouseButton
)
```

**VB**<br />
``` VB
Public Delegate Sub MouseButtonDoubleClickEventHandler ( 
	sender As Object,
	mouseLocation As Point,
	mouseButton As MouseButton
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As New MouseButtonDoubleClickEventHandler(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate void MouseButtonDoubleClickEventHandler(
	Object^ sender, 
	Point mouseLocation, 
	MouseButton mouseButton
)
```

**F#**<br />
``` F#
type MouseButtonDoubleClickEventHandler = 
    delegate of 
        sender : Object * 
        mouseLocation : Point * 
        mouseButton : MouseButton -> unit
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br /></dd><dt>mouseLocation</dt><dd>Type: System.Drawing.Point<br /></dd><dt>mouseButton</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseButton">DevCase.Core.IO.MouseButton</a><br /></dd></dl>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />