# AlbumInfo.DownloadLinks Property 
 

Gets the urls to download the album. It can be a single url, or multiple of them.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<string> DownloadLinks { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property DownloadLinks As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AlbumInfo
Dim value As ReadOnlyCollection(Of String)

value = instance.DownloadLinks

```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<String^>^ DownloadLinks {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
member DownloadLinks : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />The urls to download the album. It can be a single url, or multiple of them.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo Class</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />