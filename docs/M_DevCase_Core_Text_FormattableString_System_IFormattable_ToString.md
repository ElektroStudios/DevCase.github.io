# FormattableString.IFormattable.ToString Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
string IFormattable.ToString(
	string format,
	IFormatProvider formatProvider
)
```

**VB**<br />
``` VB
Private Function IFormattable_ToString ( 
	format As String,
	formatProvider As IFormatProvider
) As String Implements IFormattable.ToString
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormattableString
Dim format As String
Dim formatProvider As IFormatProvider
Dim returnValue As String

returnValue = CType(instance, IFormattable).ToString(format, 
	formatProvider)
```

**C++**<br />
``` C++
private:
virtual String^ IFormattable_ToString(
	String^ format, 
	IFormatProvider^ formatProvider
) sealed = IFormattable::ToString
```

**F#**<br />
``` F#
private abstract IFormattable_ToString : 
        format : string * 
        formatProvider : IFormatProvider -> string 
private override IFormattable_ToString : 
        format : string * 
        formatProvider : IFormatProvider -> string 
```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: System.String<br />\[Missing <param name="format"/> documentation for "M:DevCase.Core.Text.FormattableString.System#IFormattable#ToString(System.String,System.IFormatProvider)"\]</dd><dt>formatProvider</dt><dd>Type: System.IFormatProvider<br />\[Missing <param name="formatProvider"/> documentation for "M:DevCase.Core.Text.FormattableString.System#IFormattable#ToString(System.String,System.IFormatProvider)"\]</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Text.FormattableString.System#IFormattable#ToString(System.String,System.IFormatProvider)"\]

#### Implements
IFormattable.ToString(String, IFormatProvider)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Text_FormattableString">FormattableString Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />