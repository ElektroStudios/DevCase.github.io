# TextfileStream.Save Method (Encoding)
 

Save the lines of the current textfile, in the current textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Save(
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Overridable Sub Save ( 
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextfileStream
Dim enc As Encoding

instance.Save(enc)
```

**C++**<br />
``` C++
public:
virtual void Save(
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
abstract Save : 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 
override Save : 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to write the textfile.</dd></dl>

## Remarks
Note that the <a href="M_DevCase_Core_Text_TextfileStream_Save">Save(String, Encoding)</a> method should be called to apply any realized changes in the lines of the textfile before disposing the current <a href="T_DevCase_Core_Text_TextfileStream">TextfileStream</a> instance.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TextfileStream">TextfileStream Class</a><br /><a href="Overload_DevCase_Core_Text_TextfileStream_Save">Save Overload</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />