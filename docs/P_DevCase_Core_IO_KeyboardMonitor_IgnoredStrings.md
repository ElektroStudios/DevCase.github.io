# KeyboardMonitor.IgnoredStrings Property 
 

Gets or sets a collection of String to ignore from raising the <a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a> event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<string> IgnoredStrings { get; set; }
```

**VB**<br />
``` VB
Public Property IgnoredStrings As IEnumerable(Of String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim value As IEnumerable(Of String)

value = instance.IgnoredStrings

instance.IgnoredStrings = value
```

**C++**<br />
``` C++
public:
property IEnumerable<String^>^ IgnoredStrings {
	IEnumerable<String^>^ get ();
	void set (IEnumerable<String^>^ value);
}
```

**F#**<br />
``` F#
member IgnoredStrings : IEnumerable<string> with get, set

```


#### Property Value
Type: IEnumerable(String)<br />The collection of String to ignore.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />