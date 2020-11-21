# FileTypeMatch.FileHeader Property 
 

Gets the source file header.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public byte[] FileHeader { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property FileHeader As Byte()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileTypeMatch
Dim value As Byte()

value = instance.FileHeader

```

**C++**<br />
``` C++
public:
property array<unsigned char>^ FileHeader {
	array<unsigned char>^ get ();
}
```

**F#**<br />
``` F#
member FileHeader : byte[] with get

```


#### Property Value
Type: Byte[]<br />The source file header.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />