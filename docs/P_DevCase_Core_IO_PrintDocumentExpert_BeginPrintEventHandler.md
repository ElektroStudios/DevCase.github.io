# PrintDocumentExpert.BeginPrintEventHandler Property 
 

Gets or sets the PrintEventHandler delegate method to handle the BeginPrint event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PrintEventHandler BeginPrintEventHandler { get; set; }
```

**VB**<br />
``` VB
Public Property BeginPrintEventHandler As PrintEventHandler
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentExpert
Dim value As PrintEventHandler

value = instance.BeginPrintEventHandler

instance.BeginPrintEventHandler = value
```

**C++**<br />
``` C++
public:
property PrintEventHandler^ BeginPrintEventHandler {
	PrintEventHandler^ get ();
	void set (PrintEventHandler^ value);
}
```

**F#**<br />
``` F#
member BeginPrintEventHandler : PrintEventHandler with get, set

```


#### Property Value
Type: PrintEventHandler<br />The PrintEventHandler delegate method to handle the BeginPrint event.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />