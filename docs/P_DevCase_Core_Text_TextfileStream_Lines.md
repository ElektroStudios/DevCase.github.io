# TextfileStream.Lines Property 
 

Gets or sets the textfile lines.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual TexfileLines Lines { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property Lines As TexfileLines
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextfileStream
Dim value As TexfileLines

value = instance.Lines

instance.Lines = value
```

**C++**<br />
``` C++
public:
virtual property TexfileLines^ Lines {
	TexfileLines^ get ();
	void set (TexfileLines^ value);
}
```

**F#**<br />
``` F#
abstract Lines : TexfileLines with get, set
override Lines : TexfileLines with get, set
```


#### Property Value
Type: <a href="T_DevCase_Core_Text_TexfileLines">TexfileLines</a><br />The textfile lines.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TextfileStream">TextfileStream Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />