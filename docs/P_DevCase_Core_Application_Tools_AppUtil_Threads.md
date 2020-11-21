# AppUtil.Threads Property 
 

Gets the set of threads that are running in the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ProcessThreadCollection Threads { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Threads As ProcessThreadCollection
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ProcessThreadCollection

value = AppUtil.Threads

```

**C++**<br />
``` C++
public:
static property ProcessThreadCollection^ Threads {
	ProcessThreadCollection^ get ();
}
```

**F#**<br />
``` F#
static member Threads : ProcessThreadCollection with get

```


#### Property Value
Type: ProcessThreadCollection<br />The set of threads that are running in the current process.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim threads As ProcessThreadCollection = Threads
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />