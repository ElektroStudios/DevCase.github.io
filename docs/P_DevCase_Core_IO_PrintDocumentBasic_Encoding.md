# PrintDocumentBasic.Encoding Property 
 

Gets or sets the text encoding. 

 If no encoding is specified, the default system encoding will be used.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Encoding Encoding { get; set; }
```

**VB**<br />
``` VB
Public Property Encoding As Encoding
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentBasic
Dim value As Encoding

value = instance.Encoding

instance.Encoding = value
```

**C++**<br />
``` C++
public:
property Encoding^ Encoding {
	Encoding^ get ();
	void set (Encoding^ value);
}
```

**F#**<br />
``` F#
member Encoding : Encoding with get, set

```


#### Property Value
Type: Encoding<br />The text encoding.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentBasic">PrintDocumentBasic Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />