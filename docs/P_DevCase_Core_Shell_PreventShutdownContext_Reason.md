# PreventShutdownContext.Reason Property 
 

Gets or sets the reason for which the current application must prevent system shutdown. 

 Because users are typically in a hurry when shutting down the system, they may spend only a few seconds looking at the shutdown reasons that are displayed by the system. Therefore, it is important that your reason strings are short and clear.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Reason { get; set; }
```

**VB**<br />
``` VB
Public Property Reason As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PreventShutdownContext
Dim value As String

value = instance.Reason

instance.Reason = value
```

**C++**<br />
``` C++
public:
property String^ Reason {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Reason : string with get, set

```


#### Property Value
Type: String<br />The reason for which the current application must prevent system shutdown.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_PreventShutdownContext">PreventShutdownContext Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />