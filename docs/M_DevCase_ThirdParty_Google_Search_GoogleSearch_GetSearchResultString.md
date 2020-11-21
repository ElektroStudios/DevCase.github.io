# GoogleSearch.GetSearchResultString Method 
 

Searches the World Wide Web using `Google Search` service with the specified search options.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetSearchResultString(
	GoogleSearchOptions searchOptions
)
```

**VB**<br />
``` VB
Public Shared Function GetSearchResultString ( 
	searchOptions As GoogleSearchOptions
) As String
```

**VB Usage**<br />
``` VB Usage
Dim searchOptions As GoogleSearchOptions
Dim returnValue As String

returnValue = GoogleSearch.GetSearchResultString(searchOptions)
```

**C++**<br />
``` C++
public:
static String^ GetSearchResultString(
	GoogleSearchOptions^ searchOptions
)
```

**F#**<br />
``` F#
static member GetSearchResultString : 
        searchOptions : GoogleSearchOptions -> string 

```


#### Parameters
&nbsp;<dl><dt>searchOptions</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">DevCase.ThirdParty.Google.Search.GoogleSearchOptions</a><br />The search options to use with the `Google Search` service.</dd></dl>

#### Return Value
Type: String<br />The resulting response as a `Html` string.

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

Dim html As String = GetSearchResultString(searchOptions)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearch">GoogleSearch Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />