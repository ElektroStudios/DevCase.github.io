# KeyboardMonitor.IgnoredCharsComparer Property 
 

Gets or sets the comparison behavior for <a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredChars">IgnoredChars</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEqualityComparer<char> IgnoredCharsComparer { get; set; }
```

**VB**<br />
``` VB
Public Property IgnoredCharsComparer As IEqualityComparer(Of Char)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim value As IEqualityComparer(Of Char)

value = instance.IgnoredCharsComparer

instance.IgnoredCharsComparer = value
```

**C++**<br />
``` C++
public:
property IEqualityComparer<wchar_t>^ IgnoredCharsComparer {
	IEqualityComparer<wchar_t>^ get ();
	void set (IEqualityComparer<wchar_t>^ value);
}
```

**F#**<br />
``` F#
member IgnoredCharsComparer : IEqualityComparer<char> with get, set

```


#### Property Value
Type: IEqualityComparer(Char)<br />The comparison behavior for <a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredChars">IgnoredChars</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />