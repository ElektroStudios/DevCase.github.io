# DeviceUtil.PrinterNames Property 
 

Gets the names of all the printers installed on this computer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> PrinterNames { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property PrinterNames As IEnumerable(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of String)

value = DeviceUtil.PrinterNames

```

**C++**<br />
``` C++
public:
static property IEnumerable<String^>^ PrinterNames {
	IEnumerable<String^>^ get ();
}
```

**F#**<br />
``` F#
static member PrinterNames : IEnumerable<string> with get

```


#### Property Value
Type: IEnumerable(String)<br />The names of all the printers installed on this computer.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim printerNames As IEnumerable(Of String) = PrinterNames()
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />