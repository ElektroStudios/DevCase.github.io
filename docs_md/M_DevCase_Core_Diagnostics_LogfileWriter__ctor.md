# LogfileWriter Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Diagnostics_LogfileWriter">LogfileWriter</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LogfileWriter(
	string filepath,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filepath As String,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim enc As Encoding

Dim instance As New LogfileWriter(filepath, 
	enc)
```

**C++**<br />
``` C++
public:
LogfileWriter(
	String^ filepath, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
new : 
        filepath : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> LogfileWriter
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The log filepath.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_LogfileWriter">LogfileWriter Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />