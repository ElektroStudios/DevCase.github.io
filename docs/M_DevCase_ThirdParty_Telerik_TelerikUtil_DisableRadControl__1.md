# TelerikUtil.DisableRadControl(*T*) Method 
 

Tries to disable a Telerik RAD control in a fashion way preserving the theme styling of the control.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik">DevCase.ThirdParty.Telerik</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DisableRadControl<T>(
	T ctrl,
	Cursor newCursor = null
)
where T : RadControl

```

**VB**<br />
``` VB
Public Shared Sub DisableRadControl(Of T As RadControl) ( 
	ctrl As T,
	Optional newCursor As Cursor = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As T
Dim newCursor As CursorTelerikUtil.DisableRadControl(ctrl, newCursor)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : RadControl
static void DisableRadControl(
	T ctrl, 
	Cursor^ newCursor = nullptr
)
```

**F#**<br />
``` F#
static member DisableRadControl : 
        ctrl : 'T * 
        ?newCursor : Cursor 
(* Defaults:
        let _newCursor = defaultArg newCursor null
*)
-> unit  when 'T : RadControl

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: *T*<br />The RAD control.</dd><dt>newCursor (Optional)</dt><dd>Type: System.Windows.Forms.Cursor<br />Optionally assigns the specified Cursor to the RAD control.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The control type derived of RadControl.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
DisableRadControl(Me.RadSplitButton1, Cursors.No)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_TelerikUtil">TelerikUtil Class</a><br /><a href="N_DevCase_ThirdParty_Telerik">DevCase.ThirdParty.Telerik Namespace</a><br />