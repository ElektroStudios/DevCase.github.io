# AppUtil.ProcessPriority Property 
 

Gets or sets the overall priority category for the associated process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ProcessPriorityClass ProcessPriority { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ProcessPriority As ProcessPriorityClass
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As ProcessPriorityClass

value = AppUtil.ProcessPriority

AppUtil.ProcessPriority = value
```

**C++**<br />
``` C++
public:
static property ProcessPriorityClass ProcessPriority {
	ProcessPriorityClass get ();
	void set (ProcessPriorityClass value);
}
```

**F#**<br />
``` F#
static member ProcessPriority : ProcessPriorityClass with get, set

```


#### Property Value
Type: ProcessPriorityClass<br />The overall priority category for the associated process.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim priority As ProcessPriorityClass = ProcessPriority
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />