# CultureUtil.SetCurrentCulture Method (String)
 

Sets the culture of the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetCurrentCulture(
	string name
)
```

**VB**<br />
``` VB
Public Shared Sub SetCurrentCulture ( 
	name As String
)
```

**VB Usage**<br />
``` VB Usage
Dim name As StringCultureUtil.SetCurrentCulture(name)
```

**C++**<br />
``` C++
public:
static void SetCurrentCulture(
	String^ name
)
```

**F#**<br />
``` F#
static member SetCurrentCulture : 
        name : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The culture name (eg. "en-US").</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetCurrentCulture("en-US")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_CultureUtil">CultureUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_CultureUtil_SetCurrentCulture">SetCurrentCulture Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />