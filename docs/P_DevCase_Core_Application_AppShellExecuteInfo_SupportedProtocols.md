# AppShellExecuteInfo.SupportedProtocols Property 
 

Gets or sets a string that contains the URL protocol schemes for a given key. This can contain multiple registry values to indicate which schemes are supported. 

 This string follows the format of `scheme1:scheme2`. 

 If this list is Not empty, `file:` will be added To the String. 

 This protocol Is implicitly supported When SupportedProtocols is defined.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SupportedProtocols { get; set; }
```

**VB**<br />
``` VB
Public Property SupportedProtocols As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
Dim value As String

value = instance.SupportedProtocols

instance.SupportedProtocols = value
```

**C++**<br />
``` C++
public:
property String^ SupportedProtocols {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member SupportedProtocols : string with get, set

```


#### Property Value
Type: String<br />A string that contains the URL protocol schemes for a given key.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />