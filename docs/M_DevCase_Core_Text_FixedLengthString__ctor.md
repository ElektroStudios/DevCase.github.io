# FixedLengthString Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Text_FixedLengthString">FixedLengthString</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FixedLengthString(
	string value,
	int fixedLength,
	char paddingChar = ''
)
```

**VB**<br />
``` VB
Public Sub New ( 
	value As String,
	fixedLength As Integer,
	Optional paddingChar As Char = ""C
)
```

**VB Usage**<br />
``` VB Usage
Dim value As String
Dim fixedLength As Integer
Dim paddingChar As Char

Dim instance As New FixedLengthString(value, fixedLength, 
	paddingChar)
```

**C++**<br />
``` C++
public:
FixedLengthString(
	String^ value, 
	int fixedLength, 
	wchar_t paddingChar = L''
)
```

**F#**<br />
``` F#
new : 
        value : string * 
        fixedLength : int * 
        ?paddingChar : char 
(* Defaults:
        let _paddingChar = defaultArg paddingChar ''
*)
-> FixedLengthString
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.String<br />The string value.</dd><dt>fixedLength</dt><dd>Type: System.Int32<br />The fixed string length.</dd><dt>paddingChar (Optional)</dt><dd>Type: System.Char<br />The padding character thath fills the string.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_FixedLengthString">FixedLengthString Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />