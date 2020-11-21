# DateTimeUtil.Tomorrow Property (String)
 

Gets the date of tomorrow as a string representation using the specified format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string this[
	string format
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Tomorrow ( 
	format As String
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim format As String
Dim value As String

value = DateTimeUtil.Tomorrow(format)

```

**C++**<br />
``` C++
public:
static property String^ Tomorrow[String^ format] {
	String^ get (String^ format);
}
```

**F#**<br />
``` F#
static member Tomorrow : string with get

```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: System.String<br /></dd></dl>

#### Property Value
Type: String<br />The date of tomorrow.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tomorrow As Date = Tomorrow("MMMM dd, yyyy")
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Tomorrow">Tomorrow Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />