# AppUtil.DeleteSelfApplication Method (TimeSpan)
 

Deletes itself the application executable file after the specified time interval.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DeleteSelfApplication(
	TimeSpan delay
)
```

**VB**<br />
``` VB
Public Shared Sub DeleteSelfApplication ( 
	delay As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim delay As TimeSpanAppUtil.DeleteSelfApplication(delay)
```

**C++**<br />
``` C++
public:
static void DeleteSelfApplication(
	TimeSpan delay
)
```

**F#**<br />
``` F#
static member DeleteSelfApplication : 
        delay : TimeSpan -> unit 

```


#### Parameters
&nbsp;<dl><dt>delay</dt><dd>Type: System.TimeSpan<br />A delay interval to wait (asynchronously) before proceeding to automatic deletion.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
DeleteSelfApplication(TimeSpan.FromSeconds(5))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_DeleteSelfApplication">DeleteSelfApplication Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />