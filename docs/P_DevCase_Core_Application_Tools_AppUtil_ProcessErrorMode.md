# AppUtil.ProcessErrorMode Property 
 

Gets or sets a value that controls whether the system will handle the specified types of serious errors or whether the current process will handle them.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ProcessErrorMode ProcessErrorMode { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ProcessErrorMode As ProcessErrorMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As ProcessErrorMode

value = AppUtil.ProcessErrorMode

AppUtil.ProcessErrorMode = value
```

**C++**<br />
``` C++
public:
static property ProcessErrorMode ProcessErrorMode {
	ProcessErrorMode get ();
	void set (ProcessErrorMode value);
}
```

**F#**<br />
``` F#
static member ProcessErrorMode : ProcessErrorMode with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessErrorMode">ProcessErrorMode</a><br />The error mode of the current process.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim errMode As ProcessErrorModes = ProcessErrorMode
If Not errMode.HasFlag(ProcessErrorModes.FailCriticalErrors) Then
    ProcessErrorMode = (errMode Or ProcessErrorModes.FailCriticalErrors)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />