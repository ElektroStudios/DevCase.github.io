# PrintDocumentBasic.PrinterName Property 
 

Gets or sets the name of the printer device. 

 If no printer name is specified, the default printer device will be used.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string PrinterName { get; set; }
```

**VB**<br />
``` VB
Public Property PrinterName As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentBasic
Dim value As String

value = instance.PrinterName

instance.PrinterName = value
```

**C++**<br />
``` C++
public:
property String^ PrinterName {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member PrinterName : string with get, set

```


#### Property Value
Type: String<br />The name of the printer device.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentBasic">PrintDocumentBasic Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />