# AppOpenWithInfo.Verb Property 
 

Gets or sets the verb method for calling the application from OpenWith menu. 

 Without a verb definition specified here, the system assumes that the application supports CreateProcess, and passes the file name on the command line. 

 This functionality applies to all the verb methods, including DropTarget, ExecuteCommand, and Dynamic Data Exchange (DDE).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Verb { get; set; }
```

**VB**<br />
``` VB
Public Property Verb As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As String

value = instance.Verb

instance.Verb = value
```

**C++**<br />
``` C++
public:
property String^ Verb {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Verb : string with get, set

```


#### Property Value
Type: String<br />The verb method for calling the application from OpenWith menu.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />