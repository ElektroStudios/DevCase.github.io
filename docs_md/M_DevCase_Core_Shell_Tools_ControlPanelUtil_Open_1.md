# ControlPanelUtil.Open Method (ControlPanelItems)
 

Opens a Control Panel Item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Open(
	ControlPanelItems item
)
```

**VB**<br />
``` VB
Public Shared Sub Open ( 
	item As ControlPanelItems
)
```

**VB Usage**<br />
``` VB Usage
Dim item As ControlPanelItemsControlPanelUtil.Open(item)
```

**C++**<br />
``` C++
public:
static void Open(
	ControlPanelItems item
)
```

**F#**<br />
``` F#
static member Open : 
        item : ControlPanelItems -> unit 

```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Core_Shell_ControlPanelItems">DevCase.Core.Shell.ControlPanelItems</a><br />The control panel item.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>item</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ee330741(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ee330741(v=vs.85).aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Open(ControlPanelItems.ActionCenter)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ControlPanelUtil">ControlPanelUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ControlPanelUtil_Open">Open Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />