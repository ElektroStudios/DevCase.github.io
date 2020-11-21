# GoogleSearch.GetSearchResultStringAsync Method 
 

Asynchronously searches the World Wide Web using `Google Search` service with the specified search options.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<string> GetSearchResultStringAsync(
	GoogleSearchOptions searchOptions
)
```

**VB**<br />
``` VB
Public Shared Function GetSearchResultStringAsync ( 
	searchOptions As GoogleSearchOptions
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim searchOptions As GoogleSearchOptions
Dim returnValue As Task(Of String)

returnValue = GoogleSearch.GetSearchResultStringAsync(searchOptions)
```

**C++**<br />
``` C++
public:
static Task<String^>^ GetSearchResultStringAsync(
	GoogleSearchOptions^ searchOptions
)
```

**F#**<br />
``` F#
static member GetSearchResultStringAsync : 
        searchOptions : GoogleSearchOptions -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>searchOptions</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">DevCase.ThirdParty.Google.Search.GoogleSearchOptions</a><br />The search options to use with the `Google Search` service.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting response as a `Html` string.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim searchOptions As New GoogleSearchOptions With {
    .SearchTerm = "Hello World",
    .Language = GoogleLanguage.EN,
    .NumberOfResults = GoogleSearchOptions.MaxNumberOfResults,
    .FilterResults = False,
    .InputEncoding = Encoding.GetEncoding("ISO-8859-1"),
    .OutputEncoding = Encoding.GetEncoding("ISO-8859-1")
}

Dim html As String = Await GetSearchResultStringAsync(searchOptions, page:=0)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearch">GoogleSearch Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />