# PrintDocumentExpert.PrintPageEventHandler Property 
 

Gets or sets the PrintPageEventHandler delegate method to handle the PrintPage event.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PrintPageEventHandler PrintPageEventHandler { get; set; }
```

**VB**<br />
``` VB
Public Property PrintPageEventHandler As PrintPageEventHandler
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentExpert
Dim value As PrintPageEventHandler

value = instance.PrintPageEventHandler

instance.PrintPageEventHandler = value
```

**C++**<br />
``` C++
public:
property PrintPageEventHandler^ PrintPageEventHandler {
	PrintPageEventHandler^ get ();
	void set (PrintPageEventHandler^ value);
}
```

**F#**<br />
``` F#
member PrintPageEventHandler : PrintPageEventHandler with get, set

```


#### Property Value
Type: PrintPageEventHandler<br />The PrintPageEventHandler delegate method to handle the PrintPage event.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />