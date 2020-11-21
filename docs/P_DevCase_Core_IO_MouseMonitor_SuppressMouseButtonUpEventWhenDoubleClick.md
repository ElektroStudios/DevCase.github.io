# MouseMonitor.SuppressMouseButtonUpEventWhenDoubleClick Property 
 

** ONLY FOR TESTING PURPOSES ** 

 Gets or sets a value indicating whether to suppress the last `MouseUp` event of when a double-click occurs. 

 If this value is set to `true` (`True` in Visual Basic), the application will send the events in this order for a Double-Click: 

`MouseDown`, `MouseUp`, `MouseDown`, `MouseDoubleClick`

 If this value is set to `false` (`False` in Visual Basic), the application will send the events in this order for a Double-Click: `MouseDown`, `MouseUp`, `MouseDown`, `MouseUp`, `MouseDoubleClick`

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool SuppressMouseButtonUpEventWhenDoubleClick { get; set; }
```

**VB**<br />
``` VB
Public Property SuppressMouseButtonUpEventWhenDoubleClick As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseMonitor
Dim value As Boolean

value = instance.SuppressMouseButtonUpEventWhenDoubleClick

instance.SuppressMouseButtonUpEventWhenDoubleClick = value
```

**C++**<br />
``` C++
public:
property bool SuppressMouseButtonUpEventWhenDoubleClick {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member SuppressMouseButtonUpEventWhenDoubleClick : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if MouseUp event is suppressed; `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />