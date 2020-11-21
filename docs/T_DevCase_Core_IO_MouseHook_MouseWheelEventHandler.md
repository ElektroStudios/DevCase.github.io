# MouseHook.MouseWheelEventHandler Delegate
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate void MouseWheelEventHandler(
	Object sender,
	MouseWheelDirection wheelDirection
)
```

**VB**<br />
``` VB
Public Delegate Sub MouseWheelEventHandler ( 
	sender As Object,
	wheelDirection As MouseWheelDirection
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As New MouseWheelEventHandler(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate void MouseWheelEventHandler(
	Object^ sender, 
	MouseWheelDirection wheelDirection
)
```

**F#**<br />
``` F#
type MouseWheelEventHandler = 
    delegate of 
        sender : Object * 
        wheelDirection : MouseWheelDirection -> unit
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Object<br /></dd><dt>wheelDirection</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseWheelDirection">DevCase.Core.IO.MouseWheelDirection</a><br /></dd></dl>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />