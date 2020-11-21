# KeyboardMonitor.IgnoredKeys Property 
 

Gets or sets a collection of Keys to ignore from raising the <a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a> event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<Keys> IgnoredKeys { get; set; }
```

**VB**<br />
``` VB
Public Property IgnoredKeys As IEnumerable(Of Keys)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim value As IEnumerable(Of Keys)

value = instance.IgnoredKeys

instance.IgnoredKeys = value
```

**C++**<br />
``` C++
public:
property IEnumerable<Keys>^ IgnoredKeys {
	IEnumerable<Keys>^ get ();
	void set (IEnumerable<Keys>^ value);
}
```

**F#**<br />
``` F#
member IgnoredKeys : IEnumerable<Keys> with get, set

```


#### Property Value
Type: IEnumerable(Keys)<br />The collection of Keys to ignore.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />