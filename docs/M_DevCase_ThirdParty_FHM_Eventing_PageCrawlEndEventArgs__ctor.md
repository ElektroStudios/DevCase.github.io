# PageCrawlEndEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlEndEventArgs">PageCrawlEndEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM_Eventing">DevCase.ThirdParty.FHM.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PageCrawlEndEventArgs(
	SearchQuery searchQuery,
	int searchPage,
	IList<AlbumInfo> albums
)
```

**VB**<br />
``` VB
Public Sub New ( 
	searchQuery As SearchQuery,
	searchPage As Integer,
	albums As IList(Of AlbumInfo)
)
```

**VB Usage**<br />
``` VB Usage
Dim searchQuery As SearchQuery
Dim searchPage As Integer
Dim albums As IList(Of AlbumInfo)

Dim instance As New PageCrawlEndEventArgs(searchQuery, 
	searchPage, albums)
```

**C++**<br />
``` C++
public:
PageCrawlEndEventArgs(
	SearchQuery^ searchQuery, 
	int searchPage, 
	IList<AlbumInfo^>^ albums
)
```

**F#**<br />
``` F#
new : 
        searchQuery : SearchQuery * 
        searchPage : int * 
        albums : IList<AlbumInfo> -> PageCrawlEndEventArgs
```


#### Parameters
&nbsp;<dl><dt>searchQuery</dt><dd>Type: <a href="T_DevCase_ThirdParty_FHM_SearchQuery">DevCase.ThirdParty.FHM.SearchQuery</a><br />The search query used.</dd><dt>searchPage</dt><dd>Type: System.Int32<br />The index of the search page crawled.</dd><dt>albums</dt><dd>Type: System.Collections.Generic.IList(<a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a>)<br />A collection of <a href="T_DevCase_ThirdParty_FHM_AlbumInfo">AlbumInfo</a> that contains the information of the albums that were crawled.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlEndEventArgs">PageCrawlEndEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_FHM_Eventing">DevCase.ThirdParty.FHM.Eventing Namespace</a><br />