# DateTimeUtil.Timestamp Property 
 

Gets the current time stamp, in `ISO 8601` format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Timestamp { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Timestamp As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = DateTimeUtil.Timestamp

```

**C++**<br />
``` C++
public:
static property String^ Timestamp {
	String^ get ();
}
```

**F#**<br />
``` F#
static member Timestamp : string with get

```


#### Property Value
Type: String<br />The resulting time stamp.

## Remarks
<a href="http://en.wikipedia.org/wiki/ISO_8601" target="_blank">http://en.wikipedia.org/wiki/ISO_8601</a>

## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />