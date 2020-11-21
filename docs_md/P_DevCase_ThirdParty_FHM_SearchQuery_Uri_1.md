# SearchQuery.Uri Property (Int32)
 

Gets the <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Uri">Uri</a> that represents this search query.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Uri this[
	int searchPage
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Uri ( 
	searchPage As Integer
) As Uri
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SearchQuery
Dim searchPage As Integer
Dim value As Uri

value = instance.Uri(searchPage)

```

**C++**<br />
``` C++
public:
property Uri^ Uri[int searchPage] {
	Uri^ get (int searchPage);
}
```

**F#**<br />
``` F#
member Uri : Uri with get

```


#### Parameters
&nbsp;<dl><dt>searchPage</dt><dd>Type: System.Int32<br />The index of the search page parameter.</dd></dl>

#### Property Value
Type: Uri<br />The <a href="P_DevCase_ThirdParty_FHM_SearchQuery_Uri">Uri</a> that represents this search query.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_SearchQuery">SearchQuery Class</a><br /><a href="Overload_DevCase_ThirdParty_FHM_SearchQuery_Uri">Uri Overload</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />