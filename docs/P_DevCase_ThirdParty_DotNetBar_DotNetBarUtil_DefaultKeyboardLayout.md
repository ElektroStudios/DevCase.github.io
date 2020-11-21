# DotNetBarUtil.DefaultKeyboardLayout Property 
 

Gets the default layout for a KeyboardControl control.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetBar">DevCase.ThirdParty.DotNetBar</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Keyboard DefaultKeyboardLayout { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property DefaultKeyboardLayout As Keyboard
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Keyboard

value = DotNetBarUtil.DefaultKeyboardLayout

```

**C++**<br />
``` C++
public:
static property Keyboard^ DefaultKeyboardLayout {
	Keyboard^ get ();
}
```

**F#**<br />
``` F#
static member DefaultKeyboardLayout : Keyboard with get

```


#### Property Value
Type: Keyboard<br />The default layout for a KeyboardControl control.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim kbd As New KeyboardControl
kbd.Keyboard = DefaultKeyboardLayout()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetBar_DotNetBarUtil">DotNetBarUtil Class</a><br /><a href="N_DevCase_ThirdParty_DotNetBar">DevCase.ThirdParty.DotNetBar Namespace</a><br />