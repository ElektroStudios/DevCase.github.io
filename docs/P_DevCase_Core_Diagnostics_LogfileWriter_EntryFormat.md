# LogfileWriter.EntryFormat Property 
 

Gets or sets the format of a log entry. {0}=Date, {1}=Time, {2}=Event, {3}=Message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string EntryFormat { get; set; }
```

**VB**<br />
``` VB
Public Property EntryFormat As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As LogfileWriter
Dim value As String

value = instance.EntryFormat

instance.EntryFormat = value
```

**C++**<br />
``` C++
public:
property String^ EntryFormat {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member EntryFormat : string with get, set

```


#### Property Value
Type: String<br />The format of a log entry.

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_LogfileWriter">LogfileWriter Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />