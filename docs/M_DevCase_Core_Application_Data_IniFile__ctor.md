# IniFile Constructor (FileInfo, Encoding)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Data_IniFile">IniFile</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniFile(
	FileInfo fileinfo,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	fileinfo As FileInfo,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim fileinfo As FileInfo
Dim enc As Encoding

Dim instance As New IniFile(fileinfo, 
	enc)
```

**C++**<br />
``` C++
public:
IniFile(
	FileInfo^ fileinfo, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
new : 
        fileinfo : FileInfo * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IniFile
```


#### Parameters
&nbsp;<dl><dt>fileinfo</dt><dd>Type: System.IO.FileInfo<br />The initialization file (INI).</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The encoding to read/write the INI file.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniFile">IniFile Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniFile__ctor">IniFile Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />