# NumericSequenceFormatter.Format Method 
 

Converts the value of a specified object to an equivalent string representation using specified format and culture-specific formatting information.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Format(
	string frmt,
	Object arg,
	IFormatProvider formatProvider
)
```

**VB**<br />
``` VB
Public Function Format ( 
	frmt As String,
	arg As Object,
	formatProvider As IFormatProvider
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As NumericSequenceFormatter
Dim frmt As String
Dim arg As Object
Dim formatProvider As IFormatProvider
Dim returnValue As String

returnValue = instance.Format(frmt, arg, 
	formatProvider)
```

**C++**<br />
``` C++
public:
virtual String^ Format(
	String^ frmt, 
	Object^ arg, 
	IFormatProvider^ formatProvider
) sealed
```

**F#**<br />
``` F#
abstract Format : 
        frmt : string * 
        arg : Object * 
        formatProvider : IFormatProvider -> string 
override Format : 
        frmt : string * 
        arg : Object * 
        formatProvider : IFormatProvider -> string 
```


#### Parameters
&nbsp;<dl><dt>frmt</dt><dd>Type: System.String<br />A format string containing formatting specifications.</dd><dt>arg</dt><dd>Type: System.Object<br />An object to format.</dd><dt>formatProvider</dt><dd>Type: System.IFormatProvider<br />An object that supplies format information about the current instance.</dd></dl>

#### Return Value
Type: String<br />The string representation of the value of *arg*, formatted as specified by *frmt* and *formatProvider*.

#### Implements
ICustomFormatter.Format(String, Object, IFormatProvider)<br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The provided value is not of type Integer().</td></tr><tr><td>ArgumentNullException</td><td>frmt</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_NumericSequenceFormatter">NumericSequenceFormatter Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />