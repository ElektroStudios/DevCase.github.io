# ArchiveInfo.PackedSize Property 
 

Gets the packed size, in bytes, of the compressed archive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long PackedSize { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property PackedSize As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ArchiveInfo
Dim value As Long

value = instance.PackedSize

```

**C++**<br />
``` C++
public:
property long long PackedSize {
	long long get ();
}
```

**F#**<br />
``` F#
member PackedSize : int64 with get

```


#### Property Value
Type: Int64<br />The packed size, in bytes, of the compressed archive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo Class</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />