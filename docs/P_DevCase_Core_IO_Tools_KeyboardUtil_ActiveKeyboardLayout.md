# KeyboardUtil.ActiveKeyboardLayout Property 
 

Gets the active input locale identifier (formerly called the keyboard layout) for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr ActiveKeyboardLayout { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ActiveKeyboardLayout As IntPtr
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IntPtr

value = KeyboardUtil.ActiveKeyboardLayout

```

**C++**<br />
``` C++
public:
static property IntPtr ActiveKeyboardLayout {
	IntPtr get ();
}
```

**F#**<br />
``` F#
static member ActiveKeyboardLayout : IntPtr with get

```


#### Property Value
Type: IntPtr<br />The active input locale identifier (formerly called the keyboard layout) for the current thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim kbdLayout As IntPtr = ActiveKeyboardLayout()
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />