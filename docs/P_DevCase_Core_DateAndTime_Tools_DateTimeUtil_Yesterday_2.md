# DateTimeUtil.Yesterday Property (String, IFormatProvider)
 

Gets the date of yesterday as a string representation using the specified format and provider.

**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string this[
	string format,
	IFormatProvider provider
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Yesterday ( 
	format As String,
	provider As IFormatProvider
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim format As String
Dim provider As IFormatProvider
Dim value As String

value = DateTimeUtil.Yesterday(format, provider)

```

**C++**<br />
``` C++
public:
static property String^ Yesterday[String^ format, IFormatProvider^ provider] {
	String^ get (String^ format, IFormatProvider^ provider);
}
```

**F#**<br />
``` F#
static member Yesterday : string with get

```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: System.String<br /></dd><dt>provider</dt><dd>Type: System.IFormatProvider<br /></dd></dl>

#### Property Value
Type: String<br />The date of yesterday.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ci As New CultureInfo("en-US")
Dim yesterday As Date = Yesterday("MMMM dd, yyyy", ci)
```


## See Also


#### Reference
<a href="T_DevCase_Core_DateAndTime_Tools_DateTimeUtil">DateTimeUtil Class</a><br /><a href="Overload_DevCase_Core_DateAndTime_Tools_DateTimeUtil_Yesterday">Yesterday Overload</a><br /><a href="N_DevCase_Core_DateAndTime_Tools">DevCase.Core.DateAndTime.Tools Namespace</a><br />