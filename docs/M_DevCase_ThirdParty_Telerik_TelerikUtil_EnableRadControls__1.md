# TelerikUtil.EnableRadControls(*T*) Method 
 

Enables the specified Telerik RAD controls that were previously disabled calling <a href="M_DevCase_ThirdParty_Telerik_TelerikUtil_DisableRadControl__1">DisableRadControl(T)(T, Cursor)</a>, preserving the theme styling of the control.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik">DevCase.ThirdParty.Telerik</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EnableRadControls<T>(
	T[] ctrls,
	Cursor newCursor = null
)
where T : RadControl

```

**VB**<br />
``` VB
Public Shared Sub EnableRadControls(Of T As RadControl) ( 
	ctrls As T(),
	Optional newCursor As Cursor = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrls As T()
Dim newCursor As CursorTelerikUtil.EnableRadControls(ctrls, newCursor)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : RadControl
static void EnableRadControls(
	array<T>^ ctrls, 
	Cursor^ newCursor = nullptr
)
```

**F#**<br />
``` F#
static member EnableRadControls : 
        ctrls : 'T[] * 
        ?newCursor : Cursor 
(* Defaults:
        let _newCursor = defaultArg newCursor null
*)
-> unit  when 'T : RadControl

```


#### Parameters
&nbsp;<dl><dt>ctrls</dt><dd>Type: *T*[]<br />An Array of RAD controls.</dd><dt>newCursor (Optional)</dt><dd>Type: System.Windows.Forms.Cursor<br />Optionally assigns the specified Cursor to the RAD controls.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The control type derived of RadControl.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
EnableRadControls({Me.RadSplitButton1}, Cursors.Arrow)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_TelerikUtil">TelerikUtil Class</a><br /><a href="N_DevCase_ThirdParty_Telerik">DevCase.ThirdParty.Telerik Namespace</a><br />