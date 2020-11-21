# ArchiveInfo.FileCount Property 
 

Gets the amount of files contained inside the compressed archive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint FileCount { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property FileCount As UInteger
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ArchiveInfo
Dim value As UInteger

value = instance.FileCount

```

**C++**<br />
``` C++
public:
property unsigned int FileCount {
	unsigned int get ();
}
```

**F#**<br />
``` F#
member FileCount : uint32 with get

```


#### Property Value
Type: UInt32<br />The amount of files contained inside the compressed archive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo Class</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />