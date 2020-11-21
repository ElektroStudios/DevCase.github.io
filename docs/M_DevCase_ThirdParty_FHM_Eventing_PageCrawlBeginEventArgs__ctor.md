# PageCrawlBeginEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlBeginEventArgs">PageCrawlBeginEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM_Eventing">DevCase.ThirdParty.FHM.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PageCrawlBeginEventArgs(
	SearchQuery searchQuery,
	int searchPage
)
```

**VB**<br />
``` VB
Public Sub New ( 
	searchQuery As SearchQuery,
	searchPage As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim searchQuery As SearchQuery
Dim searchPage As Integer

Dim instance As New PageCrawlBeginEventArgs(searchQuery, 
	searchPage)
```

**C++**<br />
``` C++
public:
PageCrawlBeginEventArgs(
	SearchQuery^ searchQuery, 
	int searchPage
)
```

**F#**<br />
``` F#
new : 
        searchQuery : SearchQuery * 
        searchPage : int -> PageCrawlBeginEventArgs
```


#### Parameters
&nbsp;<dl><dt>searchQuery</dt><dd>Type: <a href="T_DevCase_ThirdParty_FHM_SearchQuery">DevCase.ThirdParty.FHM.SearchQuery</a><br />The search query used.</dd><dt>searchPage</dt><dd>Type: System.Int32<br />The index of the search page.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlBeginEventArgs">PageCrawlBeginEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_FHM_Eventing">DevCase.ThirdParty.FHM.Eventing Namespace</a><br />