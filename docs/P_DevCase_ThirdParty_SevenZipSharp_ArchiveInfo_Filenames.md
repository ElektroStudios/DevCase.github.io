# ArchiveInfo.Filenames Property 
 

Gets the filenames contained inside the compressed archive.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<string> Filenames { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Filenames As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ArchiveInfo
Dim value As ReadOnlyCollection(Of String)

value = instance.Filenames

```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<String^>^ Filenames {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
member Filenames : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />The filenames contained inside the compressed archive.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_ArchiveInfo">ArchiveInfo Class</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />