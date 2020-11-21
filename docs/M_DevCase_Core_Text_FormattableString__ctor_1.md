# FormattableString Constructor (String, Object[])
 

Initializes a new instance of the <a href="T_DevCase_Core_Text_FormattableString">FormattableString</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FormattableString(
	string format,
	params Object[] args
)
```

**VB**<br />
``` VB
Public Sub New ( 
	format As String,
	ParamArray args As Object()
)
```

**VB Usage**<br />
``` VB Usage
Dim format As String
Dim args As Object()

Dim instance As New FormattableString(format, 
	args)
```

**C++**<br />
``` C++
public:
FormattableString(
	String^ format, 
	... array<Object^>^ args
)
```

**F#**<br />
``` F#
new : 
        format : string * 
        args : Object[] -> FormattableString
```


#### Parameters
&nbsp;<dl><dt>format</dt><dd>Type: System.String<br />A composite format string.</dd><dt>args</dt><dd>Type: System.Object[]<br />An object array that contains the objects to format.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_FormattableString">FormattableString Class</a><br /><a href="Overload_DevCase_Core_Text_FormattableString__ctor">FormattableString Overload</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />