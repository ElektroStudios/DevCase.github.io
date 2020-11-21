# GoogleSearch.GetSearchResult Method 
 

Searches the World Wide Web using `Google Search` service with the specified search options.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<GoogleSearchResult> GetSearchResult(
	GoogleSearchOptions searchOptions
)
```

**VB**<br />
``` VB
Public Shared Function GetSearchResult ( 
	searchOptions As GoogleSearchOptions
) As List(Of GoogleSearchResult)
```

**VB Usage**<br />
``` VB Usage
Dim searchOptions As GoogleSearchOptions
Dim returnValue As List(Of GoogleSearchResult)

returnValue = GoogleSearch.GetSearchResult(searchOptions)
```

**C++**<br />
``` C++
public:
static List<GoogleSearchResult^>^ GetSearchResult(
	GoogleSearchOptions^ searchOptions
)
```

**F#**<br />
``` F#
static member GetSearchResult : 
        searchOptions : GoogleSearchOptions -> List<GoogleSearchResult> 

```


#### Parameters
&nbsp;<dl><dt>searchOptions</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">DevCase.ThirdParty.Google.Search.GoogleSearchOptions</a><br />The search options to use with the `Google Search` service.</dd></dl>

#### Return Value
Type: List(<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchResult">GoogleSearchResult</a>)<br />A List(T) that represents the search results.

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

Dim searchResults As List(Of GoogleSearchResult) = GetSearchResult(searchOptions)
Dim resultCount As Integer

For Each result As GoogleSearchResult In searchResults
    Console.WriteLine("[{0:000}] Url: {1}; Title: {2}; Description: {3}", Interlocked.Increment(resultCount), result.Url, result.Title, result.Description)
Next result

Console.WriteLine("Finished.")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearch">GoogleSearch Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />