# FileType.Signatures Property 
 

Gets or sets the filetype signatures. 

 A signature is data used to identify or verify the format (content) of a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<FileSignature> Signatures { get; set; }
```

**VB**<br />
``` VB
Public Property Signatures As List(Of FileSignature)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileType
Dim value As List(Of FileSignature)

value = instance.Signatures

instance.Signatures = value
```

**C++**<br />
``` C++
public:
property List<FileSignature^>^ Signatures {
	List<FileSignature^>^ get ();
	void set (List<FileSignature^>^ value);
}
```

**F#**<br />
``` F#
member Signatures : List<FileSignature> with get, set

```


#### Property Value
Type: List(<a href="T_DevCase_Core_IO_FileSignature">FileSignature</a>)<br />The filetype signatures.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileType">FileType Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />