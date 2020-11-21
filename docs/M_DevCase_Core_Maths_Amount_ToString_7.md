# Amount.ToString Method (String, IFormatProvider)
 

Returns a String that represents this <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ToString(
	string format,
	IFormatProvider formatProvider
)
```

**VB**<br />
``` VB
Public Function ToString ( 
	format As String,
	formatProvider As IFormatProvider
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim format As String
Dim formatProvider As IFormatProvider
Dim returnValue As String

returnValue = instance.ToString(format, 
	formatProvider)
```

**C++**<br />
``` C++
public:
virtual String^ ToString(
	String^ format, 
	IFormatProvider^ formatProvider
) sealed
```

**F#**<br />
``` F#
abstract ToString : 
        format : string * 
        formatProvider : IFormatProvider -> string 
override ToString : 
        format : string * 
        formatProvider : IFormatProvider -> string 
```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: System.String<br />The format to use. -or- A null reference (Nothing in Visual Basic) to use the default format defined.</dd><dt>formatProvider</dt><dd>Type: System.IFormatProvider<br />The provider to use to format the value. -or- A null reference (a null reference (`Nothing` in Visual Basic) in Visual Basic) to obtain the numeric format information from the current locale setting of the operating system.</dd></dl>

#### Return Value
Type: String<br />A String that represents this instance.

#### Implements
IFormattable.ToString(String, IFormatProvider)<br />

## Remarks
Valid format strings are 'GG', 'GN', 'GS', 'NG', 'NN' or 'NS', where the first letter represents the value formatting (General, Numeric), and the second letter represents the unit formatting (General, Name, Symbol); or a custom number format with 'UG', 'UN' or 'US' (UnitGeneral, UnitName or UnitSymbol) representing the unit (i.e. "#,##0.00 UL"). 

 The format string can also contains a '|' followed by a unit to convert to.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="Overload_DevCase_Core_Maths_Amount_ToString">ToString Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />