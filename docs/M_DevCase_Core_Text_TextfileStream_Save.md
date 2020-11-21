# TextfileStream.Save Method (String, Encoding)
 

Save the lines of the current textfile, in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Save(
	string filepath,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Overridable Sub Save ( 
	filepath As String,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextfileStream
Dim filepath As String
Dim enc As Encoding

instance.Save(filepath, enc)
```

**C++**<br />
``` C++
public:
virtual void Save(
	String^ filepath, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
abstract Save : 
        filepath : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 
override Save : 
        filepath : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The target filepath where to save the text.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to write the textfile.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TextfileStream">TextfileStream Class</a><br /><a href="Overload_DevCase_Core_Text_TextfileStream_Save">Save Overload</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />