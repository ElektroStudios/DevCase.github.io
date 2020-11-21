# AppUtil.ThreadErrorMode Property 
 

Gets or sets a value that controls whether the system will handle the specified types of serious errors or whether the current process will handle them.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ThreadErrorMode ThreadErrorMode { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ThreadErrorMode As ThreadErrorMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As ThreadErrorMode

value = AppUtil.ThreadErrorMode

AppUtil.ThreadErrorMode = value
```

**C++**<br />
``` C++
public:
static property ThreadErrorMode ThreadErrorMode {
	ThreadErrorMode get ();
	void set (ThreadErrorMode value);
}
```

**F#**<br />
``` F#
static member ThreadErrorMode : ThreadErrorMode with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadErrorMode">ThreadErrorMode</a><br />The error mode of the current thread.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim errMode As ThreadErrorModes = ThreadErrorMode
If Not errMode.HasFlag(ThreadErrorModes.FailCriticalErrors) Then
    ThreadErrorMode = (errMode Or ThreadErrorModes.FailCriticalErrors)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />