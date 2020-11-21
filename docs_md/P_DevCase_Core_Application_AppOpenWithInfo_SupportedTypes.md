# AppOpenWithInfo.SupportedTypes Property 
 

Gets or sets the file types that the application supports. 

 Doing so enables the application to be listed in the cascade menu of the Open with dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<string> SupportedTypes { get; set; }
```

**VB**<br />
``` VB
Public Property SupportedTypes As IEnumerable(Of String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As IEnumerable(Of String)

value = instance.SupportedTypes

instance.SupportedTypes = value
```

**C++**<br />
``` C++
public:
property IEnumerable<String^>^ SupportedTypes {
	IEnumerable<String^>^ get ();
	void set (IEnumerable<String^>^ value);
}
```

**F#**<br />
``` F#
member SupportedTypes : IEnumerable<string> with get, set

```


#### Property Value
Type: IEnumerable(String)<br />The supported types.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />