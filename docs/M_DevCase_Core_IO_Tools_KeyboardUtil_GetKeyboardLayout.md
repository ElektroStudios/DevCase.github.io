# KeyboardUtil.GetKeyboardLayout Method (Int32)
 

Gets the active input locale identifier (formerly called the keyboard layout).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr GetKeyboardLayout(
	int threadId
)
```

**VB**<br />
``` VB
Public Shared Function GetKeyboardLayout ( 
	threadId As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim threadId As Integer
Dim returnValue As IntPtr

returnValue = KeyboardUtil.GetKeyboardLayout(threadId)
```

**C++**<br />
``` C++
public:
static IntPtr GetKeyboardLayout(
	int threadId
)
```

**F#**<br />
``` F#
static member GetKeyboardLayout : 
        threadId : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>threadId</dt><dd>Type: System.Int32<br />The identifier of the thread to query, or `0` to query the current thread.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the input locale identifier for the thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim kbdLayout As IntPtr = GetKeyboardLayout(0) 
Dim kbdLayout As IntPtr = GetKeyboardLayout(Process.GetCurrentProcess.Threads(0).Id)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_KeyboardUtil">KeyboardUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_KeyboardUtil_GetKeyboardLayout">GetKeyboardLayout Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />