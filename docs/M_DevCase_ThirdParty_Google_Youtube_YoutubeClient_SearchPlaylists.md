# YoutubeClient.SearchPlaylists Method 
 

Searchs playlists through Youtube that matches the specified criteria.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<SearchResult>> SearchPlaylists(
	string searchPattern,
	OrderEnum resultSorting
)
```

**VB**<br />
``` VB
Public Function SearchPlaylists ( 
	searchPattern As String,
	resultSorting As OrderEnum
) As Task(Of List(Of SearchResult))
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
Dim searchPattern As String
Dim resultSorting As OrderEnum
Dim returnValue As Task(Of List(Of SearchResult))

returnValue = instance.SearchPlaylists(searchPattern, 
	resultSorting)
```

**C++**<br />
``` C++
public:
Task<List<SearchResult^>^>^ SearchPlaylists(
	String^ searchPattern, 
	OrderEnum resultSorting
)
```

**F#**<br />
``` F#
member SearchPlaylists : 
        searchPattern : string * 
        resultSorting : OrderEnum -> Task<List<SearchResult>> 

```


#### Parameters
&nbsp;<dl><dt>searchPattern</dt><dd>Type: System.String<br />The search pattern. 

 Only playlists matching the specified title pattern will be listed.</dd><dt>resultSorting</dt><dd>Type: OrderEnum<br />A value that determines the sorting method of the resulting playlists (Sort by date, sort by relevance, etc...)</dd></dl>

#### Return Value
Type: Task(List(SearchResult))<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/youtube/v3/docs/search/list" target="_blank">http://developers.google.com/youtube/v3/docs/search/list</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com")
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim playlists As List(Of SearchResult) = Await client.SearchPlaylists("Rihanna", OrderEnum.Relevance)
Dim playlistCount As Integer

For Each playlist As SearchResult In playlists
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(playlistCount),
                              playlist.Id.PlaylistId, playlist.Snippet.Title,
                              String.Format("http://www.youtube.com/playlist?list={0}", playlist.Id.PlaylistId)))

Next playlist
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_YoutubeClient">YoutubeClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />