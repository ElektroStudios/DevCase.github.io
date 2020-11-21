# KeyboardMonitor.IgnoredStringsComparer Property 
 

Gets or sets the comparison behavior for <a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredStrings">IgnoredStrings</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEqualityComparer<string> IgnoredStringsComparer { get; set; }
```

**VB**<br />
``` VB
Public Property IgnoredStringsComparer As IEqualityComparer(Of String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim value As IEqualityComparer(Of String)

value = instance.IgnoredStringsComparer

instance.IgnoredStringsComparer = value
```

**C++**<br />
``` C++
public:
property IEqualityComparer<String^>^ IgnoredStringsComparer {
	IEqualityComparer<String^>^ get ();
	void set (IEqualityComparer<String^>^ value);
}
```

**F#**<br />
``` F#
member IgnoredStringsComparer : IEqualityComparer<string> with get, set

```


#### Property Value
Type: IEqualityComparer(String)<br />The comparison behavior for <a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredStrings">IgnoredStrings</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />