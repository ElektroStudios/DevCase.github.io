# KeyboardMonitor.HandlePastes Property 
 

Gets or sets a value that determines whether a paste operation (Ctrl+V) should be handled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool HandlePastes { get; set; }
```

**VB**<br />
``` VB
Public Property HandlePastes As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim value As Boolean

value = instance.HandlePastes

instance.HandlePastes = value
```

**C++**<br />
``` C++
public:
property bool HandlePastes {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member HandlePastes : bool with get, set

```


#### Property Value
Type: Boolean<br />A value that determines whether a paste operation (Ctrl+V) should be handled.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />