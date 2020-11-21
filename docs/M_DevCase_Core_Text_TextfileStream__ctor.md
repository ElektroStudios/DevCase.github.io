# TextfileStream Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Text_TextfileStream">TextfileStream</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TextfileStream(
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

Dim instance As New TextfileStream(filepath, 
	enc)
```

**C++**<br />
``` C++
public:
TextfileStream(
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
-> TextfileStream
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The textfile path. 

 If the path doesn't exists, the file will be created.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile. 

 If *enc* value is a null reference (`Nothing` in Visual Basic), an attempt to detect the encoding will be realized, if the attempt to detect the file encoding fails, then Default will be used.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TextfileStream">TextfileStream Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />