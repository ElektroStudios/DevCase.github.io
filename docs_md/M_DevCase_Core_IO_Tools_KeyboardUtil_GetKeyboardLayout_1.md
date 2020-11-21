# KeyboardUtil.GetKeyboardLayout Method (IntPtr)
 

Gets the active input locale identifier (formerly called the keyboard layout).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr GetKeyboardLayout(
	IntPtr threadHandle
)
```

**VB**<br />
``` VB
Public Shared Function GetKeyboardLayout ( 
	threadHandle As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim threadHandle As IntPtr
Dim returnValue As IntPtr

returnValue = KeyboardUtil.GetKeyboardLayout(threadHandle)
```

**C++**<br />
``` C++
public:
static IntPtr GetKeyboardLayout(
	IntPtr threadHandle
)
```

**F#**<br />
``` F#
static member GetKeyboardLayout : 
        threadHandle : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>threadHandle</dt><dd>Type: System.IntPtr<br />A handle identifier of the thread to query, or Zero to query the current thread.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the input locale identifier for the thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim kbdLayout As IntPtr = GetKeyboardLayout(IntPtr.Zero) 
Dim kbdLayout As IntPtr = GetKeyboardLayout(New IntPtr(Process.GetCurrentProcess.Threads(0).Id))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_KeyboardUtil_GetKeyboardLayout">GetKeyboardLayout Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />