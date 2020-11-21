# KeyboardMonitor.IgnoredChars Property 
 

Gets or sets a collection of Char to ignore from raising the <a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a> event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<char> IgnoredChars { get; set; }
```

**VB**<br />
``` VB
Public Property IgnoredChars As IEnumerable(Of Char)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim value As IEnumerable(Of Char)

value = instance.IgnoredChars

instance.IgnoredChars = value
```

**C++**<br />
``` C++
public:
property IEnumerable<wchar_t>^ IgnoredChars {
	IEnumerable<wchar_t>^ get ();
	void set (IEnumerable<wchar_t>^ value);
}
```

**F#**<br />
``` F#
member IgnoredChars : IEnumerable<char> with get, set

```


#### Property Value
Type: IEnumerable(Char)<br />The collection of Char to ignore.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />