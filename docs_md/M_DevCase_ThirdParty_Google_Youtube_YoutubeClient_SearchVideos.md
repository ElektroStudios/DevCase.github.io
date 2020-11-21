# YoutubeClient.SearchVideos Method 
 

Searchs videos through Youtube that matches the specified criteria.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<SearchResult>> SearchVideos(
	string searchPattern,
	VideoDefinitionEnum videoDefinition,
	OrderEnum resultSorting
)
```

**VB**<br />
``` VB
Public Function SearchVideos ( 
	searchPattern As String,
	videoDefinition As VideoDefinitionEnum,
	resultSorting As OrderEnum
) As Task(Of List(Of SearchResult))
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
Dim searchPattern As String
Dim videoDefinition As VideoDefinitionEnum
Dim resultSorting As OrderEnum
Dim returnValue As Task(Of List(Of SearchResult))

returnValue = instance.SearchVideos(searchPattern, 
	videoDefinition, resultSorting)
```

**C++**<br />
``` C++
public:
Task<List<SearchResult^>^>^ SearchVideos(
	String^ searchPattern, 
	VideoDefinitionEnum videoDefinition, 
	OrderEnum resultSorting
)
```

**F#**<br />
``` F#
member SearchVideos : 
        searchPattern : string * 
        videoDefinition : VideoDefinitionEnum * 
        resultSorting : OrderEnum -> Task<List<SearchResult>> 

```


#### Parameters
&nbsp;<dl><dt>searchPattern</dt><dd>Type: System.String<br />The search pattern. 

 Only videos matching the specified title pattern will be listed.</dd><dt>videoDefinition</dt><dd>Type: VideoDefinitionEnum<br />A value that lets you restrict the search for HD or SD videos.</dd><dt>resultSorting</dt><dd>Type: OrderEnum<br />A value that determines the sorting method of the resulting videos (Sort by date, sort by relevance, etc...)</dd></dl>

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

Dim videos As List(Of SearchResult) = Await client.SearchVideos("Rihanna", VideoDefinitionEnum.High, OrderEnum.Relevance)
Dim videoCount As Integer

For Each video As SearchResult In videos
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(videoCount),
                              video.Id.VideoId, video.Snippet.Title,
                              String.Format("http://www.youtube.com/watch?v={0}", video.Id.VideoId)))

Next video
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_YoutubeClient">YoutubeClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />