# PageCrawlEndEventArgs.Albums Property 
 

Gets a collection of <a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a> that contains the information of the albums that were crawled.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM_Eventing">DevCase.ThirdParty.FHM.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ReadOnlyCollection<AlbumInfo> Albums { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Albums As ReadOnlyCollection(Of AlbumInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As PageCrawlEndEventArgs
Dim value As ReadOnlyCollection(Of AlbumInfo)

value = instance.Albums

```

**C++**<br />
``` C++
public:
property ReadOnlyCollection<AlbumInfo^>^ Albums {
	ReadOnlyCollection<AlbumInfo^>^ get ();
}
```

**F#**<br />
``` F#
member Albums : ReadOnlyCollection<AlbumInfo> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a>)<br />A collection of <a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a> that contains the information of the albums that were crawled.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlEndEventArgs">PageCrawlEndEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_FHM_Eventing">DevCase.ThirdParty.FHM.Eventing Namespace</a><br />