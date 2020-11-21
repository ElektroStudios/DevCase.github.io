# PrintDocumentExpert.QueryPageSettingsEventHandler Property 
 

Gets or sets the QueryPageSettingsEventHandler delegate method to handle the BeginPrint event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public QueryPageSettingsEventHandler QueryPageSettingsEventHandler { get; set; }
```

**VB**<br />
``` VB
Public Property QueryPageSettingsEventHandler As QueryPageSettingsEventHandler
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentExpert
Dim value As QueryPageSettingsEventHandler

value = instance.QueryPageSettingsEventHandler

instance.QueryPageSettingsEventHandler = value
```

**C++**<br />
``` C++
public:
property QueryPageSettingsEventHandler^ QueryPageSettingsEventHandler {
	QueryPageSettingsEventHandler^ get ();
	void set (QueryPageSettingsEventHandler^ value);
}
```

**F#**<br />
``` F#
member QueryPageSettingsEventHandler : QueryPageSettingsEventHandler with get, set

```


#### Property Value
Type: QueryPageSettingsEventHandler<br />The PrintEventHandler delegate method to handle the QueryPageSettings event.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />