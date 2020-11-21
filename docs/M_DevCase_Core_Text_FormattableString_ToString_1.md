# FormattableString.ToString Method (IFormatProvider)
 

Returns a String that represents this <a href="T_DevCase_Core_Text_FormattableString">FormattableString</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ToString(
	IFormatProvider formatProvider
)
```

**VB**<br />
``` VB
Public Function ToString ( 
	formatProvider As IFormatProvider
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormattableString
Dim formatProvider As IFormatProvider
Dim returnValue As String

returnValue = instance.ToString(formatProvider)
```

**C++**<br />
``` C++
public:
String^ ToString(
	IFormatProvider^ formatProvider
)
```

**F#**<br />
``` F#
member ToString : 
        formatProvider : IFormatProvider -> string 

```


#### Parameters
&nbsp;<dl><dt>formatProvider</dt><dd>Type: System.IFormatProvider<br />An object that supplies culture-specific formatting information.</dd></dl>

#### Return Value
Type: String<br />A String that represents this <a href="T_DevCase_Core_Text_FormattableString">FormattableString</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_FormattableString">FormattableString Class</a><br /><a href="Overload_DevCase_Core_Text_FormattableString_ToString">ToString Overload</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />