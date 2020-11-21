# SearchQuery Constructor (String, String, String)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_FHM_SearchQuery">SearchQuery</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SearchQuery(
	string genre = "all",
	string country = "all",
	string year = "all"
)
```

**VB**<br />
``` VB
Public Sub New ( 
	Optional genre As String = "all",
	Optional country As String = "all",
	Optional year As String = "all"
)
```

**VB Usage**<br />
``` VB Usage
Dim genre As String
Dim country As String
Dim year As String

Dim instance As New SearchQuery(genre, country, 
	year)
```

**C++**<br />
``` C++
public:
SearchQuery(
	String^ genre = L"all", 
	String^ country = L"all", 
	String^ year = L"all"
)
```

**F#**<br />
``` F#
new : 
        ?genre : string * 
        ?country : string * 
        ?year : string 
(* Defaults:
        let _genre = defaultArg genre "all"
        let _country = defaultArg country "all"
        let _year = defaultArg year "all"
*)
-> SearchQuery
```


#### Parameters
&nbsp;<dl><dt>genre (Optional)</dt><dd>Type: System.String<br />The music genre. Default value is: "all"</dd><dt>country (Optional)</dt><dd>Type: System.String<br />The country of the band/artist. Default value is: "all"</dd><dt>year (Optional)</dt><dd>Type: System.String<br />The year that the album has been released. Default value is: "all"</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FHM_SearchQuery">SearchQuery Class</a><br /><a href="Overload_DevCase_ThirdParty_FHM_SearchQuery__ctor">SearchQuery Overload</a><br /><a href="N_DevCase_ThirdParty_FHM">DevCase.ThirdParty.FHM Namespace</a><br />