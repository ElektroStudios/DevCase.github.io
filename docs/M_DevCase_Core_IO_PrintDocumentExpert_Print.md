# PrintDocumentExpert.Print Method 
 

Prints the current document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Print()
```

**VB**<br />
``` VB
Public Overridable Sub Print
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentExpert

instance.Print()
```

**C++**<br />
``` C++
public:
virtual void Print()
```

**F#**<br />
``` F#
abstract Print : unit -> unit 
override Print : unit -> unit 
```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>No printer device is installed.</td></tr><tr><td>Exception</td><td>Printer name is not valid.</td></tr><tr><td>Exception</td><td>The 'PrintDocumentExpert.PrintPageEventHandler' property must be set before calling the 'PrintDocumentExpert.Print()' method.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />