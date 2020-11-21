# IniFile Constructor (String, Encoding)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Data_IniFile">IniFile</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniFile(
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

Dim instance As New IniFile(filepath, 
	enc)
```

**C++**<br />
``` C++
public:
IniFile(
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
-> IniFile
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The initialization file (INI) path.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The encoding to read/write the INI file.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniFile">IniFile Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniFile__ctor">IniFile Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />