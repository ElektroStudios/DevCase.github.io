# ShortcutFileInfo.TargetDisplayName Property 
 

Gets the display name of the target file or directory. 

 Returns a empty string if the target does not exist.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string TargetDisplayName { get; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public ReadOnly Property TargetDisplayName As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim value As String

value = instance.TargetDisplayName

```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ TargetDisplayName {
	String^ get ();
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member TargetDisplayName : string with get

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.IO.ShortcutFileInfo.TargetDisplayName"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />