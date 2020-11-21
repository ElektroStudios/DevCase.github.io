# KeyboardUtil.ActiveKeyboardLayoutName Property 
 

Gets the name of the active input locale identifier (formerly called the keyboard layout) for the system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ActiveKeyboardLayoutName { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ActiveKeyboardLayoutName As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = KeyboardUtil.ActiveKeyboardLayoutName

```

**C++**<br />
``` C++
public:
static property String^ ActiveKeyboardLayoutName {
	String^ get ();
}
```

**F#**<br />
``` F#
static member ActiveKeyboardLayoutName : string with get

```


#### Property Value
Type: String<br />The name of the active input locale identifier (formerly called the keyboard layout) for the system.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim kbdLayoutName As String = ActiveKeyboardLayoutName() ' Result: 00000409 ( U.S. English )
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />