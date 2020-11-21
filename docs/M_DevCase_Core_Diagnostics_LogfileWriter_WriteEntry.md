# LogfileWriter.WriteEntry Method 
 

Writes a new entry on the logfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void WriteEntry(
	TraceEventType eventType,
	string message
)
```

**VB**<br />
``` VB
Public Sub WriteEntry ( 
	eventType As TraceEventType,
	message As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As LogfileWriter
Dim eventType As TraceEventType
Dim message As String

instance.WriteEntry(eventType, message)
```

**C++**<br />
``` C++
public:
void WriteEntry(
	TraceEventType eventType, 
	String^ message
)
```

**F#**<br />
``` F#
member WriteEntry : 
        eventType : TraceEventType * 
        message : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>eventType</dt><dd>Type: System.Diagnostics.TraceEventType<br />The type of event.</dd><dt>message</dt><dd>Type: System.String<br />The message to log.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_LogfileWriter">LogfileWriter Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />