# ControlHintInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_ControlHintInfo">ControlHintInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ControlHintInfo(
	string text,
	Font font,
	Color forecolor,
	ControlHintType hintType
)
```

**VB**<br />
``` VB
Public Sub New ( 
	text As String,
	font As Font,
	forecolor As Color,
	hintType As ControlHintType
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim font As Font
Dim forecolor As Color
Dim hintType As ControlHintType

Dim instance As New ControlHintInfo(text, font, 
	forecolor, hintType)
```

**C++**<br />
``` C++
public:
ControlHintInfo(
	String^ text, 
	Font^ font, 
	Color forecolor, 
	ControlHintType hintType
)
```

**F#**<br />
``` F#
new : 
        text : string * 
        font : Font * 
        forecolor : Color * 
        hintType : ControlHintType -> ControlHintInfo
```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The hint text.</dd><dt>font</dt><dd>Type: System.Drawing.Font<br />The text font.</dd><dt>forecolor</dt><dd>Type: System.Drawing.Color<br />The text forecolor.</dd><dt>hintType</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ControlHintType">DevCase.Core.Application.UserInterface.ControlHintType</a><br />The control-hint type.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlHintInfo">ControlHintInfo Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />