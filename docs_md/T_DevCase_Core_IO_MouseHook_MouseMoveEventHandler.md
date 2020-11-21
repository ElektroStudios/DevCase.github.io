# MouseHook.MouseMoveEventHandler Delegate
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate void MouseMoveEventHandler(
	Object sender,
	Point mouseLocation
)
```

**VB**<br />
``` VB
Public Delegate Sub MouseMoveEventHandler ( 
	sender As Object,
	mouseLocation As Point
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As New MouseMoveEventHandler(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate void MouseMoveEventHandler(
	Object^ sender, 
	Point mouseLocation
)
```

**F#**<br />
``` F#
type MouseMoveEventHandler = 
    delegate of 
        sender : Object * 
        mouseLocation : Point -> unit
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br /></dd><dt>mouseLocation</dt><dd>Type: System.Drawing.Point<br /></dd></dl>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />