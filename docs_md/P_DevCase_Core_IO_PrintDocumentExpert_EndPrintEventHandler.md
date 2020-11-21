# PrintDocumentExpert.EndPrintEventHandler Property 
 

Gets or sets the PrintEventHandler delegate method to handle the BeginPrint event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PrintEventHandler EndPrintEventHandler { get; set; }
```

**VB**<br />
``` VB
Public Property EndPrintEventHandler As PrintEventHandler
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentExpert
Dim value As PrintEventHandler

value = instance.EndPrintEventHandler

instance.EndPrintEventHandler = value
```

**C++**<br />
``` C++
public:
property PrintEventHandler^ EndPrintEventHandler {
	PrintEventHandler^ get ();
	void set (PrintEventHandler^ value);
}
```

**F#**<br />
``` F#
member EndPrintEventHandler : PrintEventHandler with get, set

```


#### Property Value
Type: PrintEventHandler<br />The PrintEventHandler delegate method to handle the EndPrint event.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />