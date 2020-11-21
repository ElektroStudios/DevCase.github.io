# ShortcutFileInfo.Hotkey Property 
 

Gets or sets the shortcut hotkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(0)]
[EditorAttribute(typeof(ShortcutKeysEditor), typeof(UITypeEditor))]
public Keys Hotkey { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(0)>
<EditorAttribute(GetType(ShortcutKeysEditor), GetType(UITypeEditor))>
Public Property Hotkey As Keys
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim value As Keys

value = instance.Hotkey

instance.Hotkey = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(0)]
[EditorAttribute(typeof(ShortcutKeysEditor), typeof(UITypeEditor))]
property Keys Hotkey {
	Keys get ();
	void set (Keys value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(0)>]
[<EditorAttribute(typeof(ShortcutKeysEditor), typeof(UITypeEditor))>]
member Hotkey : Keys with get, set

```


#### Property Value
Type: Keys<br />\[Missing <value> documentation for "P:DevCase.Core.IO.ShortcutFileInfo.Hotkey"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />