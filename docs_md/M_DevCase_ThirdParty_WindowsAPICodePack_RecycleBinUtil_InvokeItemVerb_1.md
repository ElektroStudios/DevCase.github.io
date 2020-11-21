# RecycleBinUtil.InvokeItemVerb Method (ShellObject, String)
 

Invokes a custom verb on a ShellObject item.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InvokeItemVerb(
	ShellObject item,
	string verb
)
```

**VB**<br />
``` VB
Public Shared Sub InvokeItemVerb ( 
	item As ShellObject,
	verb As String
)
```

**VB Usage**<br />
``` VB Usage
Dim item As ShellObject
Dim verb As StringRecycleBinUtil.InvokeItemVerb(item, verb)
```

**C++**<br />
``` C++
public:
static void InvokeItemVerb(
	ShellObject^ item, 
	String^ verb
)
```

**F#**<br />
``` F#
static member InvokeItemVerb : 
        item : ShellObject * 
        verb : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: ShellObject<br />The item.</dd><dt>verb</dt><dd>Type: System.String<br />The verb to invoke on the item.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil">RecycleBinUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_WindowsAPICodePack_RecycleBinUtil_InvokeItemVerb">InvokeItemVerb Overload</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack">DevCase.ThirdParty.WindowsAPICodePack Namespace</a><br />