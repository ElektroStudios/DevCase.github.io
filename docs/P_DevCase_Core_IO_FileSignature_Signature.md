# FileSignature.Signature Property 
 

Gets or sets the signature.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Nullable<byte>[] Signature { get; set; }
```

**VB**<br />
``` VB
Public Property Signature As Nullable(Of Byte)()
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSignature
Dim value As Nullable(Of Byte)()

value = instance.Signature

instance.Signature = value
```

**C++**<br />
``` C++
public:
property array<Nullable<unsigned char>>^ Signature {
	array<Nullable<unsigned char>>^ get ();
	void set (array<Nullable<unsigned char>>^ value);
}
```

**F#**<br />
``` F#
member Signature : Nullable<byte>[] with get, set

```


#### Property Value
Type: Nullable(Byte)[]<br />The signature.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSignature">FileSignature Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />